# AI 对话流转（AI Chat Flow）

一个将 ChatGPT 聊天记录及其附件持续保存到电脑本地，并支持分类整理、管理和按需提取的浏览器用户脚本。

它不是一次性下载聊天记录。建立本地资料库后，可以持续同步新增或发生变化的 Conversation，减少重复保存。

**当前版本：3.1.44**

## 下载与安装

- **GitHub 最新正式版（3.1.44）**：[前往 Releases 下载](https://github.com/valeriobarbie759-ctrl/AI-Chat-Flow/releases/tag/v3.1.44)
- **ScriptCat 脚本猫（持续更新）**：[前往脚本猫安装](https://scriptcat.org/zh-CN/script-show-page/7424)
- **123 云盘完整安装包**：[点击下载](『来自123云盘用户的分享』链接：https://1855762805.share.123pan.cn/123pan/EKOOvd-OP2x3?pwd=f8Xw#)（提取码：`f8Xw`）
- **B 站视频教程**：[AI 对话流转 3.1 使用介绍](https://www.bilibili.com/video/BV1ahHS6DE6V/)

### 运行版与注释版

本仓库提供两种版本：

- **运行版**：用于正常安装和使用，适合普通用户。
- **注释版**：保留完整代码注释，方便阅读源码、研究实现方式，也可以上传给 ChatGPT 等 AI 工具进行分析。

两个版本功能相同，只需选择一个安装，不要同时启用。

## 主要功能

### 1. ChatGPT 对话与附件保存

**3.0 系列最大的更新：不只能保存 ChatGPT 聊天记录，现在还可以将对话中的附件一起下载到电脑本地。**

- 批量保存对话与附件
- 支持按条件筛选、选择部分对话
- 可单独保存对话、附件，或同时处理
- 增量同步，减少重复保存

### 2. Project 与自命名分类

支持 ChatGPT Project 和本地自命名规则。

可以切换主视图，按照自己的习惯组织本地资料库。

### 3. 多种文件格式

支持原始数据、JSON、Markdown、Word、PDF 等格式。

可自由决定需要长期保存的格式。

### 4. 按需提取

从本地资料库重新提取需要的对话。

本地已有对应格式时直接复制，没有现成格式时再生成。

### 5. 附件管理与一键取回

- 真实附件集中保存在 `20_文件库`
- 每条对话的 `04_附件` 提供附件清单与预览
- 通过 CMD 一键取回对应对话的全部附件
- 取回成功后 CMD 自动删除，方便全选、剪切或分享
- 支持附件检查与补充

### 6. 本地管理与任务处理

- 本地对话及附件管理
- 自命名规则与检查变化
- 归档、忽略及待处理
- 请求自动调速与任务恢复
- 任务日志与诊断信息

## 第一次使用

1. 安装 ScriptCat 等用户脚本管理器。
2. 安装 AI 对话流转运行版。
3. 打开或刷新 ChatGPT。
4. 点击页面右侧的插件入口。
5. 选择本地资料库位置。
6. 按需设置保存格式及附件功能。
7. 进入「导出」，选择对话并开始保存。

建议使用桌面版 Chrome / Edge。

## 历史版本

由于原 GitHub 账号已经无法继续使用，本仓库从 3.1.44 开始发布。

如果需要旧版 2.9.85，可以前往：

[旧版 GitHub 仓库](https://github.com/zwmqcf/chatgpt-local-sync)

ScriptCat 仍然使用原来的发布页面。

## 问题反馈

如果在使用过程中遇到问题，欢迎通过 [GitHub Issues](https://github.com/valeriobarbie759-ctrl/AI-Chat-Flow/issues) 反馈。

建议提供操作过程、实际结果，以及必要的诊断信息，方便定位问题。

也欢迎提出功能建议与改进意见。

## ❤️ 支持项目

AI 对话流转是一个免费开源的个人项目。

如果你觉得这个工具好用，或者它对你有所帮助，也欢迎通过自愿赞赏的方式支持后续的开发与维护。

无论是否赞赏，都不会影响插件的正常使用。

感谢大家的使用、建议与支持！

### 微信赞赏

![微信赞赏码](https://raw.githubusercontent.com/valeriobarbie759-ctrl/AI-Chat-Flow/main/support.png)

### 支付宝赞赏

![支付宝赞赏码](https://raw.githubusercontent.com/valeriobarbie759-ctrl/AI-Chat-Flow/main/support2.png)

## 开源许可

本项目采用 [MIT License](LICENSE) 开源。
