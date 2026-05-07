<p align="center">
  <img src="./assets/pigbun-logo.svg" alt="PigBun Partner" width="112" />
</p>

# PigBun Partner 社区

[English](./README.md)

PigBun Partner 是一个运行在你本地电脑上的 AI 合伙人系统。

它不是一个普通聊天壳。PigBun 想解决的问题是：你把一个持续目标托付给 AI 合伙人，PigBun 通过合伙人聊天、业务线、本地工具和浏览器工作台，帮你持续推进这件事。

这个公开仓库是 PigBun Partner 的社区入口：

- 反馈 Bug
- 提问和讨论
- 查看安装说明
- 跟踪路线图
- 查看已知问题和版本记录

PigBun 的核心运行时代码目前还没有开源。这个仓库的定位是公开文档、反馈入口、路线图和社区讨论区，让早期用户有一个清晰的聚集地。

## 安装

PigBun 当前以本地 Node 运行时的方式启动，并通过浏览器打开工作台。

```bash
curl -fsSL https://pigbunai.com/install.sh | bash
```

安装完成后，可以用下面的命令启动：

```bash
pigbun
```

安装脚本会做这些事情：

- 检查本地基础运行环境。
- 下载最新 alpha 运行时。
- 安装 `pigbun` 命令。
- 在本地启动 PigBun，并打开浏览器工作台。

## PigBun 适合做什么

PigBun 面向的是“托付一件持续推进的事情”，而不是只问一次问题。

当前 alpha 阶段重点：

- 和一个能记住工作上下文的 AI 合伙人对话。
- 为持续目标创建业务线。
- 让业务线从主聊天中独立推进。
- 使用 Claude Code、Codex 等本地执行器。
- 在浏览器工作台中查看进展、决策和阻塞点。

## 基座模型会显著影响稳定性

PigBun 使用的是外部 Harness 架构：它会围绕本地执行器，管理合伙人聊天、业务线、记忆、工具、活动日志和恢复路径。

这套 Harness 能提升协作、可观察性和恢复能力，但它不能抹平基座模型本身的差异。模型能力弱或者不稳定时，仍然可能出现理解目标偏差、漏步骤、不知道何时拆分业务线、工具使用不稳定、规划质量下降等问题。

所以在严肃任务中，基座模型会直接影响 PigBun AI 的运行稳定性和交付质量。

早期推荐使用：

- Claude Sonnet / Claude Opus
- GPT-5.4 / GPT-5.5
- Kimi 2.6

未来 PigBun 会支持 Kimi CLI 作为新的执行器接入路径。

## 当前状态

PigBun 仍处于 alpha 阶段。

它已经可以真实使用，但仍然会有一些边角问题：

- 安装和自动更新仍在持续加固。
- 页面文案和多语言还在持续整理。
- Claude Code 和 Codex 在不同用户电脑上的表现可能不同。
- 一些业务线流程仍可能需要用户手动引导。

如果你遇到问题，请在 Issue 中提供复现步骤和日志。

## 重要链接

- [路线图](./ROADMAP.md)
- [已知问题](./KNOWN_ISSUES.md)
- [反馈指南](./FEEDBACK.md)
- [版本记录](./CHANGELOG.md)
- [FAQ](./FAQ.md)
- [安全与隐私说明](./SECURITY.md)

## 如何反馈

具体 Bug 请使用 GitHub Issues：

- 安装失败。
- PigBun 无法启动。
- 聊天或业务线行为异常。
- 检查更新找不到最新版本。
- 页面文案让人困惑或没有翻译。

产品想法、使用问题、工作流案例和长反馈，可以使用 GitHub Discussions。

## 联系方式

公开讨论优先使用 GitHub Issues 和 Discussions。

微信联系可以扫描 PigBun AI 二维码：

<img src="./assets/wechat-qr.jpg" alt="PigBun AI 微信二维码" width="220" />

Telegram 暂时不公开私人账号。早期用户支持更建议使用公开群组或频道，避免把支持压力集中到个人私聊里。

## 目前还没有完整开源

PigBun 的核心运行时代码目前仍然是私有的，因为产品还在快速稳定阶段。

短期优先级是先把早期用户体验做稳定，再决定哪些部分适合开源。公开文档、Issue、Discussions、路线图和版本记录会持续维护在这里。
