<p align="center">

![yjtp](https://github.com/user-attachments/assets/dcc74009-c57e-4b66-9ae3-0a81fc001255)

</p>

<div align="center">

_✨ 易上手的多平台 LLM 聊天机器人及开发框架 ✨_

<a href="https://trendshift.io/repositories/12875" target="_blank"><img src="https://trendshift.io/api/badge/repositories/12875" alt="Soulter%2FAstrBot | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/Soulter/AstrBot?style=for-the-badge&color=76bad9)](https://github.com/Soulter/AstrBot/releases/latest)
<img src="https://img.shields.io/badge/python-3.10+-blue.svg?style=for-the-badge&color=76bad9" alt="python">
<a href="https://hub.docker.com/r/soulter/astrbot"><img alt="Docker pull" src="https://img.shields.io/docker/pulls/soulter/astrbot.svg?style=for-the-badge&color=76bad9"/></a>
<a  href="https://qm.qq.com/cgi-bin/qm/qr?k=wtbaNx7EioxeaqS9z7RQWVXPIxg2zYr7&jump_from=webapi&authKey=vlqnv/AV2DbJEvGIcxdlNSpfxVy+8vVqijgreRdnVKOaydpc+YSw4MctmEbr0k5"><img alt="Static Badge" src="https://img.shields.io/badge/QQ群-775869627-purple?style=for-the-badge&color=76bad9"></a>
[![wakatime](https://wakatime.com/badge/user/915e5316-99c6-4563-a483-ef186cf000c9/project/018e705a-a1a7-409a-a849-3013485e6c8e.svg?style=for-the-badge&color=76bad9)](https://wakatime.com/badge/user/915e5316-99c6-4563-a483-ef186cf000c9/project/018e705a-a1a7-409a-a849-3013485e6c8e)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.soulter.top%2Fastrbot%2Fstats&query=v&label=7%E6%97%A5%E6%B4%BB%E8%B7%83%E9%87%8F&cacheSeconds=10800&style=for-the-badge&color=3b618e)

<a href="https://github.com/Soulter/AstrBot/blob/master/README_en.md">English</a> ｜
<a href="https://github.com/Soulter/AstrBot/blob/master/README_ja.md">日本語</a> ｜
<a href="https://astrbot.app/">查看文档</a> ｜
<a href="https://github.com/Soulter/AstrBot/issues">问题提交</a>
</div>

AstrBot 是一个松耦合、异步、支持多消息平台部署、具有易用的插件系统和完善的大语言模型（LLM）接入功能的聊天机器人及开发框架。

[![star](https://gitcode.com/Soulter/AstrBot/star/badge.svg?style=for-the-badge)](https://gitcode.com/Soulter/AstrBot)

<!-- [![codecov](https://img.shields.io/codecov/c/github/soulter/astrbot?style=for-the-badge)](https://codecov.io/gh/Soulter/AstrBot)
 -->

## ✨ 近期更新

1. AstrBot 现已支持接入 [MCP](https://modelcontextprotocol.io/) 服务器！

## ✨ 主要功能

> [!NOTE]
> 🪧 我们正基于前沿科研成果，设计并实现适用于角色扮演和情感陪伴的长短期记忆模型及情绪控制模型，旨在提升对话的真实性与情感表达能力。敬请期待 `v3.6.0` 版本！

1. **大语言模型对话**。支持各种大语言模型，包括 OpenAI API、Google Gemini、Llama、Deepseek、ChatGLM 等，支持接入本地部署的大模型，通过 Ollama、LLMTuner。具有多轮对话、人格情境、多模态能力，支持图片理解、语音转文字（Whisper）。
2. **多消息平台接入**。支持接入 QQ（OneBot）、QQ 频道、微信（Gewechat）、飞书、Telegram。后续将支持钉钉、Discord、WhatsApp、小爱音响。支持速率限制、白名单、关键词过滤、百度内容审核。
3. **Agent**。原生支持部分 Agent 能力，如代码执行器、自然语言待办、网页搜索。对接 [Dify 平台](https://astrbot.app/others/dify.html)，便捷接入 Dify 智能助手、知识库和 Dify 工作流。
4. **插件扩展**。深度优化的插件机制，支持[开发插件](https://astrbot.app/dev/plugin.html)扩展功能，极简开发。已支持安装多个插件。
5. **可视化管理面板**。支持可视化修改配置、插件管理、日志查看等功能，降低配置难度。集成 WebChat，可在面板上与大模型对话。
6. **高稳定性、高模块化**。基于事件总线和流水线的架构设计，高度模块化，低耦合。

> [!TIP]
> 管理面板在线体验 Demo: [https://demo.astrbot.app/](https://demo.astrbot.app/)
> 
> 用户名: `astrbot`, 密码: `astrbot`。未配置 LLM，无法在聊天页使用大模型。

## ✨ 使用方式

#### Docker 部署

请参阅官方文档 [使用 Docker 部署 AstrBot](https://astrbot.app/deploy/astrbot/docker.html#%E4%BD%BF%E7%94%A8-docker-%E9%83%A8%E7%BD%B2-astrbot) 。

#### Windows 一键安装器部署

请参阅官方文档 [使用 Windows 一键安装器部署 AstrBot](https://astrbot.app/deploy/astrbot/windows.html) 。

#### 宝塔面板部署

请参阅官方文档 [宝塔面板部署](https://astrbot.app/deploy/astrbot/btpanel.html) 。

#### CasaOS 部署

社区贡献的部署方式。

请参阅官方文档 [CasaOS 部署](https://astrbot.app/deploy/astrbot/casaos.html) 。

#### 手动部署

推荐使用 `uv`。

```bash
git clone https://github.com/AstrBotDevs/AstrBot && cd AstrBot
pip install uv
uv run main.py
```

或者请参阅官方文档 [通过源码部署 AstrBot](https://astrbot.app/deploy/astrbot/cli.html) 。

#### Replit 部署

[![Run on Repl.it](https://repl.it/badge/github/Soulter/AstrBot)](https://repl.it/github/Soulter/AstrBot)

## ⚡ 消息平台支持情况

| 平台    | 支持性 | 详情 | 消息类型 |
| -------- | ------- | ------- | ------ |
| QQ(官方机器人接口) | ✔    | 私聊、群聊，QQ 频道私聊、群聊 | 文字、图片 |
| QQ(OneBot)      | ✔    | 私聊、群聊 | 文字、图片、语音 |
| 微信(个人号)    | ✔    | 微信个人号私聊、群聊 | 文字、图片、语音 |
| [Telegram](https://github.com/Soulter/astrbot_plugin_telegram)   | ✔    | 私聊、群聊 | 文字、图片 |
| [微信(企业微信)](https://github.com/Soulter/astrbot_plugin_wecom)    | ✔    | 私聊 | 文字、图片、语音 |
| 飞书   | ✔    | 私聊、群聊 | 文字、图片 |
| 钉钉   | ✔    | 私聊、群聊 | 文字、图片 |
| 微信对话开放平台 | 🚧    | 计划内 | - |
| Discord   | 🚧    | 计划内 | - |
| WhatsApp   | 🚧    | 计划内 | - |
| 小爱音响   | 🚧    | 计划内 | - |

## ⚡ 提供商支持情况

| 名称    | 支持性 | 类型 | 备注 |
| -------- | ------- | ------- | ------- |
| OpenAI API | ✔    | 文本生成 | 同时也支持 DeepSeek、Google Gemini、GLM（智谱）、Moonshot（月之暗面）、阿里云百炼、硅基流动、xAI 等所有兼容 OpenAI API 的服务 |
| Claude API | ✔    | 文本生成 |  |
| Google Gemini API | ✔    | 文本生成 |  |
| Dify | ✔    | LLMOps |  |
| DashScope(阿里云百炼应用) | ✔    | LLMOps |  |
| Ollama | ✔    | 模型加载器 | 本地部署 DeepSeek、Llama 等开源语言模型 |
| LM Studio | ✔    | 模型加载器 | 本地部署 DeepSeek、Llama 等开源语言模型 |
| LLMTuner | ✔    | 模型加载器 | 本地加载 lora 等微调模型 |
| OneAPI | ✔    | LLM 分发系统 |  |
| Whisper | ✔    | 语音转文本 | 支持 API、本地部署 |
| SenseVoice | ✔    | 语音转文本 | 本地部署 |
| OpenAI TTS API | ✔    | 文本转语音 |  |
| GSVI | ✔    | 文本转语音 | GPT-Sovits-Inference |
| Fishaudio | ✔    | 文本转语音 | GPT-Sovits 作者参与的项目 |
| Edge-TTS | ✔    | 文本转语音 | Edge 浏览器的免费 TTS |

## ❤️ 贡献

欢迎任何 Issues/Pull Requests！只需要将你的更改提交到此项目 ：)

### 如何贡献

你可以通过查看问题或帮助审核 PR（拉取请求）来贡献。任何问题或 PR 都欢迎参与，以促进社区贡献。当然，这些只是建议，你可以以任何方式进行贡献。对于新功能的添加，请先通过 Issue 讨论。

### 开发环境

AstrBot 使用 `ruff` 进行代码格式化和检查。

```bash
git clone https://github.com/Soulter/AstrBot
pip install pre-commit
pre-commit install
```

## 🌟 支持

- Star 这个项目！
- 在[爱发电](https://afdian.com/a/soulter)支持我！
- 在[微信](https://drive.soulter.top/f/pYfA/d903f4fa49a496fda3f16d2be9e023b5.png)支持我~

## ✨ Demo

> [!NOTE]
> 代码执行器的文件输入/输出目前仅测试了 Napcat(QQ), Lagrange(QQ)

<div align='center'>

<img src="https://github.com/user-attachments/assets/4ee688d9-467d-45c8-99d6-368f9a8a92d8" width="600">

_✨基于 Docker 的沙箱化代码执行器（Beta 测试中）✨_

<img src="https://github.com/user-attachments/assets/0378f407-6079-4f64-ae4c-e97ab20611d2" height=500>

_✨ 多模态、网页搜索、长文本转图片（可配置） ✨_

<img src="https://github.com/user-attachments/assets/8ec12797-e70f-460a-959e-48eca39ca2bb" height=100>

_✨ 自然语言待办事项 ✨_

<img src="https://github.com/user-attachments/assets/e137a9e1-340a-4bf2-bb2b-771132780735" height=150>
<img src="https://github.com/user-attachments/assets/480f5e82-cf6a-4955-a869-0d73137aa6e1" height=150>

_✨ 插件系统——部分插件展示 ✨_

<img src="https://github.com/user-attachments/assets/592a8630-14c7-4e06-b496-9c0386e4f36c" width=600>

_✨ 管理面板 ✨_

![webchat](https://drive.soulter.top/f/vlsA/ezgif-5-fb044b2542.gif)

_✨ 内置 Web Chat，在线与机器人交互 ✨_

</div>

## ⭐ Star History

> [!TIP] 
> 如果本项目对您的生活 / 工作产生了帮助，或者您关注本项目的未来发展，请给项目 Star，这是我维护这个开源项目的动力 <3

<div align="center">
    
[![Star History Chart](https://api.star-history.com/svg?repos=soulter/astrbot&type=Date)](https://star-history.com/#soulter/astrbot&Date)

</div>

## Disclaimer

1. The project is protected under the `AGPL-v3` opensource license.
2. The deployment of WeChat (personal account) utilizes [Gewechat](https://github.com/Devo919/Gewechat) service. AstrBot only guarantees connectivity with Gewechat and recommends using a WeChat account that is not frequently used. In the event of account risk control, the author of this project shall not bear any responsibility.
3. Please ensure compliance with local laws and regulations when using this project.

_私は、高性能ですから!_

