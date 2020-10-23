# install-openpose-win10-vs2017-cuda10.1-cmake-python
install openpose: win10+vs2017+cuda10.1+cmake+python

2020-10-22

在安装OpenPose的时候遇到了一些问题，最后找了一堆资料才安装好的，写了一个doc来记录一下，顺便备份在网上
主要参考了Open Pose的官方安装视频，去它的官网就可以找到，这里记录的是，我在安装时遇到的和官网视频所讲解的有差异的地方，也就是：
“视频中的 VS 我遇到的”
“视频中的 VS 我遇到的”
“视频中的 VS 我遇到的”

问题1：VS2019的安装界面不一样。
直接选 VS2017的。具体看doc文档。

问题2：OpenPose下载解压后的文件夹和网上的一些教程里的内容不一样。
去Openpose的Github官网，把整个项目的zip下载下来解压，正确的话，文件名应该是：“openpose-master.zip”
而不是：下载release里面的“openpose-1.6.0-binaries-win64-gpu-python-flir-3d_recommended.zip”

问题3：Cmake一直跑进度条。
进度条是在下载模型所以需要时间，可以慢慢等，因为服务器是国外的，就是慢。
或者，把模型下载好了，放在对应位置。
下载方法：在点击“xx.bat”之后会进入cmd的窗口下载，用鼠标选中下载地址，“Ctrl+Shift+C”就复制了链接，然后把链接放在浏览器或者迅雷里面下载，速度会快很多。


