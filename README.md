# SiglusEngine


汉化SiglusEngine的几个注意事项


1.首先找到2个key使用程序拆出ss文件


2.使用stringdump拆出程序内的文本


3.使用stringpacker打包文本


4.使用ScePacker将文件打包


5.修改游戏内容，干掉解压缩算法（之后会解决压缩问题）


如何修复文本间距问题：


修改setlocate的Japanese到chs即可



修改CreateFontW的字体和字符集编码到黑体和0x86


修改GDI32.CreateFontIndirectW的字体和字符集编码到黑体和0x86

