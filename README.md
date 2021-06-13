# 渊仔按钮 Linyuan Button

### https://linyuan.site

<!-- 相关链接 / 関連URL / Related Links:

* [Sakura Miko's Youtube channel](https://www.youtube.com/channel/UC-hM6YJuNYVAmUWxeIr9FeA)

* [Sakura Miko's Twitter](https://twitter.com/sakuramiko35) -->

## 参与完善本项目

**Rome was not built in a day.** 

欢迎参与完善这个并不成熟的项目，或者为我们提出宝贵的意见！

联系方式：Email: `pinggaikun@gmail.com`

该项目是由`樱按钮`fork而来的：[樱按钮](https://github.com/voosc/miko-button)

### 添加或修改音频

**简述**：所有的音频信息都存储在 `assets/voices.json` 中，要添加或修改音频，你需要同时修改对应的文件。

音频一律为mp3格式，存储在 `static/voices` 中。对应的URL为 `voices/`。

添加的新音频请先使用类似 Adobe Audition 的软件进行响度匹配，目前使用的标准为 ITU-R BS.1770-3，目标响度 -24LUFS，容差 2LU，最高实际峰值电平 -2dBTP。

如果需要对现有音频进行修改，建议将原音频文件删除，重新命名一个新文件，这样可以避免浏览器缓存问题。

修改音频之后请删除原音频文件。

**推荐使用 [voices.json 编辑工具](https://aka.blw.moe/voiceditor) 进行编辑。**

### 参与翻译

在渊仔按钮中，暂时去除了翻译功能。

主程序翻译在 `assets/locales` 中的三个以语言名命名的 js 文件中。

语音的翻译在 `assets/voices.json` 中。

## 部署本地开发环境

本项目是使用 Vue + NuxtJS + Vuetify 开发的。

要部署本地开发环境，请首先安装最新版本的 Node 和 Yarn 包管理器。然后，请按照下列步骤操作：

1.Fork 并 Clone 代码到本地。

2.进入代码所在目录，运行 `yarn` 安装依赖。

3.运行 `yarn dev`，启动本地开发服务器，项目将被临时部署在 `localhost:3000` 上。在代码修改过程中，本地开发服务器可以即时更新修改结果。

4.要编译可用于部署的文件，请运行 `yarn generate`，这将在 `dist` 目录生成完全静态的文件。编译完成后，您可以直接将整个 `dist` 目录部署至 Github Pages 等静态文件托管服务上。

## LICENSE

This project is modified based on the [Fubuki button](https://github.com/lonelyion/fubuki-button) and [Sakura Button](https://github.com/vbup-osc/miko-button).

> 注：若以下内容存在与GPL协议内容冲突或GPL协议内容未提及的，请按以下内容为准。

程序部分： GPL

若引用我们的项目而不修改任何内容，则引用方需在描述和README.md的任意部位提及使用我们的项目。

若修改我们项目源代码再发布，或参考我们项目内部实现发布另一个新项目，则发布方必须在该新（或修改后）项目的发布文章的首部 和 任何涉及我们项目相关内容的位置 明确声明来源于本仓库。
不得扭曲或隐藏免费且开源的事实。

<!-- 音频部分: [hololive 二次创作条款](https://www.hololive.tv/terms) -->

本项目为爱好者作品。

