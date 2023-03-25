### 2023-03-25：感谢大家的关注，该工具将持续更新新功能。即将更新的功能：配置文件保存，安卓手机连接界面文字识别。有其他需求可提issues

## OcrHelper 是一款基于PaddleOCR实现的从图片中识别出汉字，英文，数字的开源小工具。可以在复杂动态背景下识别出各种字体的文字和符号。轻松实现无侵入式获取各种软件，APP界面显示内容，准确率高达95%。

### 目前仅支持windows7及以上64位系统
[https://github.com/xksoft/OcrHelper/releases/download/1.1/win-x64-1.1.zip](https://github.com/xksoft/OcrHelper/releases/download/1.1/win-x64-1.1.zip?_blank)

### 关注公众号，免费体验更多黑科技
![qrcode_for_gh_a53a61421e9e_258](https://user-images.githubusercontent.com/24860541/224869945-18d2a500-812b-48b4-85cf-3efa133aacf1.jpg)


### 有二次开发功能扩展需求可微信联系
![wx](https://user-images.githubusercontent.com/24860541/223293827-33a9cc2f-e91c-49b0-b46a-2ba036b83f2c.jpg)



### 适用场景扩展

#### 1、直播间弹幕识别，聊天识别，根据识别到的直播间弹幕和聊天消息自动回答客户问题，节省人工成本。
![2](https://user-images.githubusercontent.com/24860541/223008429-7d06b299-1849-4e89-b1dc-d71583cf1bd7.jpg)
![3](https://user-images.githubusercontent.com/24860541/223008414-0a9d8ce2-e588-4768-84a3-344743fd05ff.jpg)



#### 2、社交群，私域流量消息管理。根据关键词实时采集客户需求，分析，引导转化。
![7](https://user-images.githubusercontent.com/24860541/223008458-d1a1c459-9954-4960-b1d0-c2405f4f7e9f.jpg)



#### 3、pdf以及不可复制场景文字内容提取。
![4](https://user-images.githubusercontent.com/24860541/223008480-1604380f-84ea-4b93-a44c-545eec8a9c8c.jpg)
![5](https://user-images.githubusercontent.com/24860541/223008491-8917fc6e-2e11-40ee-a419-38225f8e6705.jpg)
![6](https://user-images.githubusercontent.com/24860541/223008498-81ba7390-df14-416a-99cd-b4949bd5586f.jpg)


#### 打包命令
 dotnet publish -c Release -r win-x64 -p:PublishSingleFile=true --self-contained true /p:IncludeNativeLibrariesForSelfExtract=false /p:DebugType=None
