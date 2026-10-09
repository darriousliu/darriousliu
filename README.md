<div align="center">

# 👋 Hi，我是 Darrious Liu

### Kotlin Multiplatform / Android Developer

**跨平台应用 · 内容阅读 · 开源组件**

**简体中文** | [English](README-en.md)

[![Kotlin Multiplatform](https://img.shields.io/badge/Kotlin-Multiplatform-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://www.jetbrains.com/kotlin-multiplatform/)
[![Compose Multiplatform](https://img.shields.io/badge/Compose-Multiplatform-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://www.jetbrains.com/compose-multiplatform/)

</div>

---

## 👨‍💻 关于我

我主要使用 **Kotlin Multiplatform 和 Compose** 开发跨平台应用与可复用组件，关注多端 UI、内容阅读，以及 Markdown / LaTeX 的解析与渲染。

从完整的客户端应用，到公式渲染、文本解析和本地存储组件，我希望让这些能力在不同平台上复用。

### 🧰 技术栈

**语言与跨平台 UI**

`Kotlin` · `Kotlin Multiplatform` · `Compose Multiplatform`

**网络与应用基础**

`Kotlin Coroutines` · `Ktor` · `Koin` · `Coil` · `Room` · `MMKV`

**构建与发布**

`Gradle Kotlin DSL` · `GitHub Actions`

---

## 🚀 主要项目

### 🖼️ [PiPixiv](https://github.com/darriousliu/PiPixiv)

[![GitHub Stars](https://img.shields.io/github/stars/darriousliu/PiPixiv?style=flat-square&logo=github)](https://github.com/darriousliu/PiPixiv)
[![GitHub Downloads](https://img.shields.io/github/downloads/darriousliu/PiPixiv/total?style=flat-square&logo=github)](https://github.com/darriousliu/PiPixiv/releases)

基于 **Kotlin Multiplatform + Compose Multiplatform** 的第三方 Pixiv 客户端，覆盖 Android、iOS、Windows、macOS 和 Linux。

提供插画浏览与下载、小说阅读和 AI 翻译，包含阅读进度恢复、翻译缓存与任务队列，并在移动端和桌面端复用 UI 与业务模块。

👉 [源码与功能介绍](https://github.com/darriousliu/PiPixiv) · [下载版本](https://github.com/darriousliu/PiPixiv/releases)

---

### 📐 [RaTeX-CMP](https://github.com/darriousliu/RaTeX-CMP)

[![GitHub Stars](https://img.shields.io/github/stars/darriousliu/RaTeX-CMP?style=flat-square&logo=github)](https://github.com/darriousliu/RaTeX-CMP)

面向 **Compose Multiplatform** 的 LaTeX 数学公式渲染库，核心渲染能力来自 [RaTeX](https://github.com/erweixin/RaTeX)。

为 Android、iOS、JVM Desktop 和 Web JS / Wasm 提供统一的 Compose 公式展示 API，集成各平台所需的渲染依赖。

👉 [源码与接入说明](https://github.com/darriousliu/RaTeX-CMP)

---

### 💾 [mmkv-kotlin](https://github.com/darriousliu/mmkv-kotlin)

[![GitHub Stars](https://img.shields.io/github/stars/darriousliu/mmkv-kotlin?style=flat-square&logo=github)](https://github.com/darriousliu/mmkv-kotlin)

基于 [ctripcorp/mmkv-kotlin](https://github.com/ctripcorp/mmkv-kotlin) 扩展的 Kotlin Multiplatform 键值存储库。

新增 JVM Desktop 支持，并提供 Windows、macOS 和 Linux 的原生库集成与分发，让 KMP 应用在桌面端使用 MMKV。

👉 [源码与接入说明](https://github.com/darriousliu/mmkv-kotlin)

---

## 📦 其他作品

### [commonmark-kotlin](https://github.com/darriousliu/commonmark-kotlin)

基于 [commonmark-java](https://github.com/commonmark/commonmark-java) 改编的 Kotlin Multiplatform Markdown 解析与渲染库，支持 Android、iOS、JVM，包含表格、任务列表、脚注与 LaTeX 等扩展。

### [KotlinTeX](https://github.com/darriousliu/KotlinTeX) · 已归档

早期 Kotlin Multiplatform LaTeX 渲染库，基于 AndroidMath 改写并集成 FreeType。已停止维护，新项目请参考 [RaTeX-CMP](https://github.com/darriousliu/RaTeX-CMP)。

---

## 💬 交流与反馈

欢迎通过各项目的 **Issues 和 Pull Requests** 交流、反馈或参与改进。
