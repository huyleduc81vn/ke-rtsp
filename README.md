# ke-rtsp
一种基于Media Source Extensions（简称MSE）技术实现的html5实时视频直播方案。Node.js调用ffmpeg包装rtsp流，然后通过socket.io转发包装后的流，前端html5获取流数据并通过MSE把流一点一点喂给video标签进行视频播放。能够支持谷歌浏览器、火狐浏览器、Edge浏览器、安卓原生浏览器，不支持IE。高性能，支持同时转发多路视频，占用硬件资源不多。低延时，延时1s。

# 运行示例项目
    1、克隆或者下载项目到本地。
<br/>

    2、命令行进入到项目目录，执行命令node sample/index.js。
<br/>

    3、修改sample/index.html中的config对象的url参数为你的rtsp测试地址。
<br/>

    4、浏览器打开http://localhost:8080/。

# 集成到你的项目中
代码量较少，请自行加工后将源代码添加到你的项目中，npm上的代码不再更新维护。

# 流媒体服务器成品出售
现已实现流媒体直播成品软件一套，集拉流、推流、接收流、转发流、播放流功能于一体。可以免费试用，[下载地址](https://github.com/kekeqy/ke-rtsp/releases)，有详细部署操作文档。提供简单易用的SDK包，通过该SDK可快速将流媒体播放功能集成到H5应用中。服务器端可部署于window、linux、macos三大系统中，浏览器端可支持所有支持H5的平台，诸如谷歌、火狐、Safari、Edge、IE11、安卓浏览器、微信等。有需要者可以联系我，可出售授权或源代码，并提供定制开发服务。
