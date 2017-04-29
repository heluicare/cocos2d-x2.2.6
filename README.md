# cocos2d-x2.2.6
可直接编译通过的2.2.6版本

因为在一些网站上下下来的2.2.6版本编译报错如下：

Cannot open include file: 'GL/glew.h': No such file or directory
...
Cannot open include file: 'pthread.h': No such file or directory
...
Cannot open include file: 'zlib.h': No such file or directory
...

诸如此类错误提示信息，大概是项目中缺少..\cocos2dx\platform\third_party\win32这个文件 
重新下载下面这个版本，后编译通过
http://cocostudio.download.appget.cn/Cocos2D-X/cocos2d-x-2.2.6.zip
