> 本工程是基于FFmpeg4.2.3，在工程里面也有一个3.3.2的版本，有需要的可以自己去Git库里面checkout，工程17年就做好了，一直没有开源，原谅我懒，哈哈哈

#### 如何使用:

1. 在allprojects下面添加: maven { url 'https://dl.bintray.com/bookzhan/bzlib' }
2. implementation 'com.luoye.bzlib:bzffmpegcmd:1.0.4'
3. FFmpegCMDUtil.executeFFmpegCommand(String command, OnActionListener onActionListener)



English documentation：

> This project is based on FFmpeg4.2.3. There is also a version 3.3.2 in the project. If you need it, you can checkout it in the Git library. 



#### How to use:

1. Add below allprojects:maven { url 'https://dl.bintray.com/bookzhan/bzlib' }
2. implementation 'com.luoye.bzlib:bzffmpegcmd:1.0.4'
3. FFmpegCMDUtil.executeFFmpegCommand(String command, OnActionListener onActionListener)

