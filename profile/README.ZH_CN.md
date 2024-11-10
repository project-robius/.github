# Robius: 使用 Rust 进行多平台应用开发

Robius 是一个完全开源、去中心化、由社区驱动的项目，旨在实现使用 Rust 进行多平台应用程序开发。

获取更多信息，请查看：
* [Robius 手册][robius_book]
* 关于 Robius 的演讲：
  * **Robius 项目的首次状态更新和演示** ([RustNL 2024](https://2024.rustnl.org/speakers/#kevin))
    * 视频： [YouTube 链接](https://www.youtube.com/watch?v=Dg4hlfettn8)
    * 幻灯片：
      [PowerPoint (19MB)](https://github.com/project-robius/files/raw/3ac0a9d2e9f3c78ea51b4875abe02d288fa3685f/RustNL%202024%20and%20GOSIM%20Europe%202024/Robius%20Talk%20RustNL%20May%208,%202024.pptx),
      [PDF 版本 (12MB)](https://github.com/project-robius/files/blob/3ac0a9d2e9f3c78ea51b4875abe02d288fa3685f/RustNL%202024%20and%20GOSIM%20Europe%202024/Robius%20Talk%20RustNL%20May%208%2C%202024.pdf)
  * **Robrix：Matrix 聊天客户端及更多功能** ([GOSIM Europe 2024](https://europe2024.gosim.org/schedule#fediverse))
    * 视频：[YouTube 链接](https://www.youtube.com/watch?v=P8RGF942A5g)
    * 幻灯片：
      [PowerPoint (22MB)](https://github.com/project-robius/files/raw/3ac0a9d2e9f3c78ea51b4875abe02d288fa3685f/RustNL%202024%20and%20GOSIM%20Europe%202024/Robrix%20Talk%20GOSIM%20Europe%20May%206,%202024.pptx),
      [PDF 版本 (16MB)](https://github.com/project-robius/files/blob/3ac0a9d2e9f3c78ea51b4875abe02d288fa3685f/RustNL%202024%20and%20GOSIM%20Europe%202024/Robrix%20Talk%20GOSIM%20Europe%20May%206%2C%202024.pdf)
  * **介绍我们对 Robius 项目的愿景** ([GOSIM 2023](https://workshop2023.gosim.org/schedule#mobile))
    * 视频：
      [YouTube 链接](https://youtu.be/8JfOXfmwotQ?si=kLogqnaApYPNuSq8&t=6802),
      [Bilibili 链接](https://www.bilibili.com/video/BV1AN4y1Z7vs/)
    * 幻灯片：
      [PowerPoint (18MB)](https://github.com/project-robius/files/raw/041e980ec1d14bf325f1fb2ba743f8ed142a70cb/Robius%20-%20A%20Vision%20for%20Multi-platform%20App%20Development%20in%20Rust.pptx),
      [PDF 版本 (15MB)](https://github.com/project-robius/files/blob/041e980ec1d14bf325f1fb2ba743f8ed142a70cb/Robius%20-%20A%20Vision%20for%20Multi-platform%20App%20Development%20in%20Rust.pdf)

Robius 组织也作为一个非正式[^1]的工作组：提供一个友好的公共空间，用于收集和讨论与改进和推进 Rust 应用开发体验相关的资源。

[^1]: Robius 与 Rust 项目或 Rust 基金会没有官方关联。

> 有问题？想参与？有兴趣贡献？    
> 欢迎加入我们在 [Matrix 聊天 Robius 空间](https://matrix.to/#/#robius:matrix.org)的友好社区。

## 我们的愿景

我们相信 Rust 编程语言是下一代应用程序开发者的正确选择，但该语言生态系统需要更多的关注和改进，以使其在应用程序开发领域（特别是在移动平台上）成为一流的选择。

我们展望的未来是：
1. Rust 开发者可以创建安全、优美且健壮的应用程序，这些应用程序能在各种平台（尤其是移动平台）上高效运行。
2. 使用其他语言的前端开发者能够顺利过渡到 Rust 的精彩世界，通过无缝的过渡体验帮助克服通常与 Rust 相关的陡峭学习曲线。
3. 扩展和加强 Rust 生态系统，向其他领域的 Rust 专家展示 Rust 非常适合高效的应用程序开发，而不仅仅是低级系统和嵌入式编程。

### 名称的由来？
*Robius* 这个名字来源于拉丁语单词 [robius](http://latin-dictionary.net/definition/33662/robius-robia-robium)，意思是红色的，如公牛、小麦、锈等的颜色。
这与我们选择的编程语言 Rust（锈）在颜色上有很好的联系。

Robius 的发音与 Mobius 相押韵，我们的标志/图标灵感来自于"Rust"和"莫比乌斯带（Mobius strip）"这两个词的组合。

> 是的，*严格来说*，原始的德语名称是 Möbius，但我们使用美式发音，带有长"o"音："Roe-bee-us" / ˈɹoʊˈbiəs。

## 当前状态
Robius 是一个全新的愿景 —— 我们正在起步阶段。

目前，最好的入门方式是直接使用其中一个[推荐的用户界面工具包（UI toolkit）](#主要社区项目)来构建应用程序的界面并定义其用户体验（UX）行为。
目前，除了用户界面之外的所有功能都需要您自己添加缺失的部分，例如：网络连接、异步多任务处理，以及对其他设备外设或系统服务的访问。

所有开发都在这里公开进行，所以请经常回来查看更新！
我们计划在 2024 年初至中期推出完整的 Robius 系统栈（应用程序之下的所有内容）的预览版（pre-alpha），这将使得在用户界面工具包之外更容易访问和集成其他平台/操作系统功能。

### 平台支持 📲 🖥️ 🌐 💻 🖱️ ⌨️ 

[➡️ 点击这里查看表格 ⬅️](https://project-robius.github.io/book/status.html#platform-support)，了解哪些项目在哪些平台上支持哪些功能。

## 主要社区项目
Robius 生态系统由几个独立的项目组成，这些项目可以组合成一个完整的系统栈，以实现在纯 Rust 环境下跨多个平台的快速、无痛应用程序开发。
组件之间松散耦合，允许开发者（在未来）自定义使用哪些组件来构成底层系统：

* [Makepad] 是一个正在积极开发中的跨平台用户界面工具包，提供混合保留模式和即时模式的用户界面模型。
  * 快速开发周期：由于采用自定义的最小依赖集，编译时间*非常*快，加上用于实时设计的自定义 DSL（领域特定语言），支持用户界面元素的热重载。
  * Makepad Studio：使用 Makepad 本身构建的 IDE（集成开发环境）原型，具有独特功能，如用于在窗口内 UI 应用程序实时重载的跨进程共享纹理、文件/窗口视图的停靠标签、超流畅的代码折叠等。
  * Makepad 框架：高性能小部件和最小化、零/低开销平台抽象的（不断增长的）集合。

* [Dioxus] 是一个受 React 启发的跨平台、可用于生产环境的用户界面工具包，使用名为 RSX 的自定义金属语言以类似 HTML 的风格声明用户界面元素/布局。
  * 通过一组可互换的目标渲染器支持*多个*平台，包括桌面、网络应用、静态网站、文本用户界面、实时视图和移动端。
  * 快速且内存高效，具有完美的灯塔（lighthouse）分数，性能比 Node 或 Python 高出数个数量级。
  * 出色的内置状态管理抽象。
  * 使用原生 CSS 或您选择的 CSS 框架（如 Tailwind）进行简单、熟悉的样式设计。

* [Osiris] 是一组用于在各种操作系统服务和平台特定功能之上开发沉浸式应用程序的 Rust 接口。
  * Osiris 旨在为 Rust 应用程序提供一种简单的规范方式来访问平台功能，如存储、网络、多媒体（视频、音频、相机）、地理位置、设备方向（加速度计、陀螺仪）、定时器和闹钟、通知、剪贴板、拖放等。
  * `osi`：主要的 Rust 包，提供对操作系统接口的直接访问。更高级别的 Rust 抽象即将推出，在更多平台的原始接口完成之后。
  * Osiris 提供的构建工具可以：
    1. 设置新的项目目录，自动生成平台特定集成组件的脚手架，这些组件可以在创建后进行自定义。
    2. 生成符合各平台政策的应用程序构件，即可以发布到常见应用商店（Google Play、Apple App Store、Microsoft Store 等）的包。

## 感兴趣的代码仓库

Robius 旨在提供整个应用程序底层系统栈的完整*参考设计*，将提供架构概述和详细文档。

我们还计划提供两类实际应用程序：
1. 旗舰应用：具有清晰用户界面设计、精致用户体验和功能性业务逻辑的完整、功能齐全的应用程序。这些应用程序将可以发布到平台应用商店。
2. 简单演示：一系列展示几个关键功能的基础示例应用程序，包含模拟组件。

#### 旗舰应用
* [Robrix：Robius Matrix 聊天客户端](https://github.com/project-robius/robrix)
  * 目前正在积极开发中，欢迎帮助！
  * 该应用程序的需求将成为 Robius 开发的主要驱动力。
* [Moxin：开源大语言模型（LLM）的本地浏览器](https://github.com/project-robius/moxin)
  * 目前正在积极开发中，欢迎帮助！
  * 允许本地运行大语言模型并与每个模型的 AI 聊天机器人对话，使用 WasmEdge 运行时作为大语言模型后端运行时。

#### 简单演示应用
* [`makepad_social_media_feed`]：社交媒体信息流的移动端用户界面演示。
  * 另请参见 Makepad 的最新示例：[Makepad 新闻信息流](https://github.com/makepad/makepad/tree/master/examples/news_feed)。
* [`makepad_taobao`]：类似淘宝或 eBay 的在线购物应用程序的用户界面演示。
* [`todo_makepad`]：基础待办事项清单应用程序。
* [`makepad_wechat`]：类似微信、WhatsApp、Signal 等聊天应用程序的用户界面演示。
* [`makepad_tiktok`]：抖音风格短视频浏览应用程序的用户界面演示。
* [`makepad_widgets_sample`]：展示 Makepad 提供的各种小部件的应用程序。
* [`makepad_image_manipulation`]：展示 Makepad 高性能图像变换功能的演示。
* 7 GUIs：7 GUIs 基准测试的部分实现，基于 [Makepad](https://github.com/project-robius/makepad_7guis) 和 [Dioxus](https://github.com/project-robius/dioxus_7guis)。

更多示例，请查看 [Dioxus 示例应用程序](https://github.com/DioxusLabs/example-projects)和 [Makepad 示例应用程序](https://github.com/makepad/makepad/tree/master/examples)的广泛集合。
Osiris 特定的示例即将推出。

## 贡献
我们欢迎任何人的贡献、想法和建议！我们也愿意帮助您在 Robius 组织的保护伞下托管和维护您的项目。

我们特别感谢将手册内容和 README 翻译成其他语言！如果您会说多种语言并愿意慷慨相助，请联系我们。

如上所述，请随时通过 [Matrix 聊天的 Robius 空间](https://matrix.to/#/#robius:matrix.org)联系我们友好的开发者社区。

<!-- 链接引用 -->
[robius_book]: https://project-robius.github.io/book/
[Makepad]: https://makepad.nl/
[Makepad_github]: https://github.com/makepad/makepad
[Dioxus]: https://dioxuslabs.com/
[Dioxus_github]: https://github.com/DioxusLabs/dioxus
[Osiris]: https://github.com/osiris-apis
[ylong]: https://gitee.com/openharmony/commonlibrary_rust_ylong_runtime
[rayon]: https://crates.io/crates/rayon

[`makepad_social_media_feed`]: https://github.com/project-robius/makepad_social_media_feed
[`makepad_widgets_sample`]: https://github.com/project-robius/makepad_widgets_sample
[`makepad_taobao`]: https://github.com/project-robius/makepad_taobao
[`makepad_wechat`]: https://github.com/project-robius/makepad_wechat
[`todo_makepad`]: https://github.com/project-robius/todo_makepad
[`makepad_tiktok`]: https://github.com/project-robius/makepad_tiktok
[`makepad_image_manipulation`]: https://github.com/project-robius/makepad_image_manipulation
