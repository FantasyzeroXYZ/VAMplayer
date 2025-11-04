# VAMplayer
用于语言学习的网页播放器，目前还在测试中，功能还不完善
## 功能（待完善）
* 可以选择播放带字幕的内容
  * 视频播放
  * 音频播放（有问题待修复，不能正常运行）
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
## 项目结构
```
📁 VAMplayer
├── index.html
├── README.md
├── 📁 .github/workflows
│   └── deploy.yml
├── 📁 assets
├── .gitignore
├── index.html   
├── 📁 build
├── 📁 css  
├── 📁 dict
└── 📁 js
```
## 来源
* 词典API出处
  * https://freedictionaryapi.com/
  * [freeDictionaryAPI](https://github.com/meetDeveloper/freeDictionaryAPI)
* 使用[kuromoji.js](https://github.com/takuyaa/kuromoji.js)进行日语分词