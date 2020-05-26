# mapleIM-apicloud-demo
## 简介：
maple-IM 为[蓝蘑云](http://www.lmaple.com)推出的即时通讯消息系统，包括了聊天室聊天, 消息送礼, 单聊，群聊，黑名单，用户查询等功能，适用于娱乐，游戏，教育等实时IM场景中；Maple-IM支持快速私有化部署，一键部署上线。

----------
- 完整的 API 文档见 [文档中心](http://doc.lmaple.com/maple-im-apicloud-sdk.html)

----------
这个开源项目演示了如何快速集成 maple-IM SDK 到 apicloud 中，实现在apicloud应用中即时消息通讯。

在这个示例项目中包含了以下功能：
- 加入消息房间和离开消息房间；
- 发送自定义消息；
- 获取房间用户信息；
- 获取房间用户总人数；
- 打开／关闭禁言用户；
- 踢出用户；


## 运行示例程序
首先在 联系对接群 **701150764**, [蓝蘑云后台管理](http://account.lmaple.com) 注册账号，获取到 appID。将 appID 填写进 config.xml的appId的value中；

<img src="http://doc.lmaple.com/image/maple-rtc-apicloud_2.png" width="500">

```
  <feature name="mapleRTC">
    <param name="appId" value="##########"/>
  </feature>
```

然后在 [maple-IM SDK](http://sdk.lmaple.com/MapleIM_ApiCloud_SDK_Release.zip) 下载 **maple-im  SDK for Apicloud**，解压后将其中的 **mapleIM.zip** 文件夹复制到本项目的指定目录下。

- 建议在[apicloud 控制平台](https://www.apicloud.com/)进行云编译运行；

- 额外自行加入该项目源码到Android Studio 和 Xcode编译运行； 


## 运行环境
- Android Studio 2.0+ 或 Xcode 8.0+
- [apicloud 控制平台](https://www.apicloud.com/)云编译
- 真实 Android / iOS 设备

## 联系我们

对接qq群  **701150764**

## Demo
注：android可以测试运行，iOS 打包的为开发者账号，只能部分机子可以测试运行；

android:
[Android 即时消息演示Demo](http://fir.kcrtu.com/mapleImAndroid)

iOS:
[iOS 即时消息演示Demo](http://fir.kcrtu.com/mapleIMiOS)


