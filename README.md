
# *视频下载器*
[English README]()
***
![](https://img.shields.io/github/release/JackieCooo/VideoDownloader?style=flat-square)
![](https://img.shields.io/github/last-commit/JackieCooo/VideoDownloader?style=flat-square)
![](https://img.shields.io/static/v1?label=Pyqt5&message=v5.14.2&color=blue?style=flat-square)
![](https://img.shields.io/github/license/JackieCooo/VideoDownloader?style=flat-square&color=yellow)

## *目录*
- [项目简介](#项目简介)
    - [软件预览](#软件预览)
    - [软件简介](#软件简介)
    - [支持情况](#支持情况)
- [安装](#安装)
- [打包](#打包)
- [更新日志](#更新日志)
- [已知bug](#已知bug)
- [要增加的新功能](#要增加的新功能)
- [赞助](#赞助)
- [参考文章](#参考文章)

## *项目简介*

### *软件预览*
这里放图片  

### *软件简介*
本项目是基于Python 3.8开发的开源项目，针对目前主流的视频网站，可对支持的视频视频网站的视频进行下载。用户界面使用Pyqt5进行设计，全新UI 2.0界面，扁平化设计语言，简洁美观。

### *支持情况*
|平台|版本|最高下载画质|备注|
|:----:|:----:|:----:|:----:|
|Bilibili|1.0|1080p||
|腾讯视频|1.0|1080p|720p以上需要会员登录|


## *安装*
步骤1  
确保电脑已安装FFmpeg组件，本软件依赖此组件进行视频文件的处理。  
FFmpeg下载：  
![](./README%20icons/ffmepg_logo.png) [官网下载](http://ffmpeg.org/download.html)
![](./README%20icons/baiducloud_logo.png) [百度云]()

步骤2  
本项目基于Python 3.8开发，请确保电脑已安装Python 3.8以上版本。  
Python下载：  
![](./README%20icons/python_logo.png) [官网下载](https://www.python.org/downloads/)
![](./README%20icons/baiducloud_logo.png) [百度云]()  

步骤3  
本项目使用以下第三方包：Pyqt5、PIL  
在Window下载：  
```commandline
pip install Pyqt5
```
在Linux下载：  
```commandline
pip3 install Pyqt5
```
在MacOS下载：  
```commandline
pip3 install Pyqt5
```
请确保运行程序前安装完全。  

## *打包*
若要对软件进行最终打包，需安装Pyinstaller第三方包  
安装完成后在项目根目录下打开cmd命令行，键入以下代码：  
```commandline
pyinstaller -F -w Main.py
```
等待几分钟即可完成软件打包  

## *更新日志*

## *已知bug*
- [X] 队列超过一个视频源时，画质选择会有冲突
- [ ] 下载队列超过一个视频会有缩略图显示问题
- [ ] 有多线程问题
- [ ] 皮肤切换时，设置区内无法涉及
- [ ] 未解决队列与下载中队列的动态调整问题

## *要增加的功能*
- [ ] 多线程下载
- [ ] 支持登陆
- [ ] 加入动画系统

## *赞助*
![支付宝](./icons/Alipay.png)
![微信](./icons/wechat_pay.png)

## *参考文章*
