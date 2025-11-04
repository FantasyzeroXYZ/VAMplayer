# VAMplayer
用于语言学习的网页播放器，目前还在测试中，功能还不完善
## 功能（待完善）
* 视频播放
  * 上下句切换
  * 字幕选择跳转
* 音频播放
  * 支持滚动字幕显示
* 字幕点击一键查词
  * 支持英语点击查词
  * 支持日语分词和分词后点击查词
* 支持Anki制卡
  * 单词
  * 单词释义
  * 字幕句子
  * 视频截图
  * 音频片段
## 使用说明（待完善）
### anki连接说明
* 请在ankiconnect插件设置里的"webCorsOriginList"里加上`"https://fantasyzeroxyz.github.io"`后重新启动anki,如下所示：
```
"webCorsOriginList": [
    "https://fantasyzeroxyz.github.io"
]
```
* 如果是安卓手机则需要安装[AnkiconnectAndroid](https://github.com/KamWithK/AnkiconnectAndroid)，安装后在里面的设置里的CORS Host中填上`https://fantasyzeroxyz.github.io`
* 若页面中显示anki已连接则说明连接成功
### 关于安卓端使用
* 安卓端推荐用Via浏览器访问进行anki制卡。因为本身没什么优化加上其他浏览器限制的原因现阶段制卡使用还是有点卡顿。
## 更新计划
* [ ] 给全屏播放加上字幕
* [ ] 视频画面录制截取
* [ ] 通过开发外部插件脚本拓展灵活性

## 项目结构
```
📁 VAMplayer
├── 📁 assets  
├── index.html   
├── 📁 css    
├── 📁 dict   # 本地词典部分（暂时空白）
├── 📁 docs   # 说明文档（暂时空白）
├── 📁 js     
├── 📁 kuromoji # kuromoji资源
└── index.html 
```
## 来源
* 词典API出处
  * https://freedictionaryapi.com/
  * [freeDictionaryAPI](https://github.com/meetDeveloper/freeDictionaryAPI)
* 使用[kuromoji.js](https://github.com/takuyaa/kuromoji.js)进行日语分词