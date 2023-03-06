## OcrHelper 是一款基于PaddleOCR实现的从图片中识别出汉字，英文，数字的开源小工具。可以在复杂动态背景下识别出各种字体的文字和符号。轻松实现无侵入式获取各种软件，APP界面显示内容，准确率高达95%。

### 目前仅支持windows7及以上64位系统
[https://github.com/xksoft/OcrHelper/releases/download/1.0/win-x64.zip](https://github.com/xksoft/OcrHelper/releases/download/1.0/win-x64.zip?_blank)


### 适用场景扩展

#### 1、直播间弹幕识别，聊天识别，根据识别到的直播间弹幕和聊天消息自动回答客户问题，节省人工成本。

![QQ截图20230301171435](https://user-images.githubusercontent.com/24860541/222360211-11187450-aa7b-4b59-b850-3780e9870192.jpg)
![QQ截图20230301171345](https://user-images.githubusercontent.com/24860541/222360226-695e3bed-5eb4-4365-870f-84023920c611.jpg)


#### 2、社交群，私域流量消息管理。根据关键词实时采集客户需求，分析，引导转化。
![QQ截图20230301170909](https://user-images.githubusercontent.com/24860541/222362025-5843f29f-7aea-4e31-bfef-c67e17d338ab.jpg)


#### 3、pdf以及不可复制场景文字内容提取。
![QQ截图20230301171139](https://user-images.githubusercontent.com/24860541/222362212-6114143d-2b29-4935-a55c-186dcd2c06de.jpg)
![QQ截图20230301170739](https://user-images.githubusercontent.com/24860541/222362231-59a2f19d-170d-46c7-9898-27cb60b6100e.jpg)

#### 打包命令
 dotnet publish -c Release -r win-x64 -p:PublishSingleFile=true --self-contained true /p:IncludeNativeLibrariesForSelfExtract=false /p:DebugType=None
