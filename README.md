<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
  <img src="assets/logo.png" alt="AI 产品开箱工具包" width="180">
</picture>

# AI 产品从想法到上线 · 开箱工具包

**不懂代码，也能做出并上线一个 AI 产品**

你只管想清楚要做什么；写代码、跑测试、做界面、部署上线，交给编码 AI。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
![面向人群](https://img.shields.io/badge/面向-非技术产品经理-green.svg)
![系统](https://img.shields.io/badge/系统-macOS-lightgrey.svg)
![工具](https://img.shields.io/badge/工具-Claude_Code_%7C_Codex_%7C_Pi-black.svg)
![语言](https://img.shields.io/badge/文档-中文-red.svg)

[快速开始](#-快速开始) · [六个阶段](#-六个阶段ai-做什么你做什么) · [怎么知道 AI 没糊弄](#-怎么知道-ai-没糊弄) · [详细操作手册](./开始看这里.md)

</div>

---

## ✨ 这是什么

一个装着"规则"的空项目文件夹：一张 AI 规则卡、三份技术手册、一个自检脚本。

你用编码 AI 工具打开它，贴一句启动句。AI 就按规则卡扮演你的技术合伙人：先帮你把需求问清楚，再按阶段写代码、做界面、部署上线，每个阶段交证据给你核对。你只做业务判断和少数必须本人做的事（申请 Key、实名认证、确认花钱）。

## 🎯 适合做什么

**适合：**

- 不懂代码的产品经理、学生，想把一个 AI 产品想法真正做出来
- 做 MVP：网页形态的 AI 产品（生成、对话、分析类），电脑和手机浏览器都能用
- 上线给小范围用户试用，同时在线几十人以内
- 用 Mac 电脑

**不在范围内：**

- 中大型项目、高并发、多地容灾
- 对公众正式运营（自有域名、公开推广、收费）：需要另办 ICP 备案等手续。本工具包默认用腾讯云开发分配的网址，不需要自己的域名，也就不用备案
- Windows 电脑（暂不支持）

## 🚀 快速开始

**1. 下载这个工具包**

点本页右上方绿色的 **Code** 按钮 → **Download ZIP**，解压到电脑上。解压后的文件夹就是你的产品项目，里面的文件不要改。

**2. 装一个编码 AI 工具**

它和网页版聊天 AI 的区别是：能在你电脑上装东西、跑程序、改文件。网页版 AI 做不到，不能用。推荐三个，选一个就行：

| 工具 | 说明 |
| --- | --- |
| [Claude Code](https://claude.com/claude-code) | 这套工具包在它上面走过完整的开发流程，最稳 |
| [Codex](https://openai.com/codex/) | 会自动读规则卡 `AGENTS.md` |
| [Pi](https://pi.dev/) | 开源的终端编码工具，会自动读 `AGENTS.md`；可接 Kimi、MiniMax 等国内模型 |

规则写在文件夹里，不绑定某个工具或模型。其他能读写文件、执行命令的工具也可以；工具里接 DeepSeek 等国内模型也行。

**3. 放 PRD（可选）**

有 PRD 就放进 `projects/我的第一个产品/docs/PRD/` 文件夹，Word、Markdown、PDF 都行。没有就跳过，AI 会问你几个问题帮你写出来。有设计稿或喜欢的界面截图，可以放进旁边的 `设计参考/` 文件夹。开工时 AI 会问你产品名，把"我的第一个产品"这个文件夹改成你的产品名。

**4. 用工具打开文件夹，贴这句话**

```text
请读取项目根目录的 AGENTS.md，按其中"启动流程"开始。
```

之后每一步 AI 都会告诉你"下一步做什么"。看不懂就回："用产品语言再说一遍"。

> 📖 每一步的详细说明见 [开始看这里.md](./开始看这里.md)。

## 📄 许可

[MIT License](./LICENSE) © 2025 hubooooooo
