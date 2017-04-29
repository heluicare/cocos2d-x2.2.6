# cocos2d-x2.2.6
可直接编译通过的2.2.6版本

\n\n因为在一些网站上下下来的2.2.6版本编译报错如下：

\n\nCannot open include file: 'GL/glew.h': No such file or directory
\n...
\nCannot open include file: 'pthread.h': No such file or directory
\n...
\nCannot open include file: 'zlib.h': No such file or directory
\n...

\n\n诸如此类错误提示信息，大概是项目中缺少..\cocos2dx\platform\third_party\win32这个文件 
\n重新下载下面这个版本，后编译通过
\nhttp://cocostudio.download.appget.cn/Cocos2D-X/cocos2d-x-2.2.6.zip
