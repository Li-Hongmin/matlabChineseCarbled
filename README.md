# Matlab 中文乱码解决办法

进入matlab的目录了找到 bin目录下 
替换 lcdata.xml文件即可

注意：必须要求系统语言为中文，如果是英文的系统照样乱码，实测无效。
另外：如果删掉文件中40～47行如下内容，就可以用英文界面的matlab了。
“<locale name="zh_CN" encoding="GB2312" xpg_name="zh_CN.GB2312">
	<alias name="zh-CN"/>

	<alias name="zh-Hans"/>

	<alias name="zh-Hans-CN"/>

</locale>“
