# Deskgram 2 任务管理器

任务管理器是 Deskgram 2 中用于监控 Telegram 自动化流程的看板。它把任务表格、筛选、状态、统计和快速控制动作放在一个操作视图里。

[Deskgram 2 中文总览](https://github.com/Deskgram-2/deskgram-2-telegram-automation-zh) | [官网](https://deskgram2.com/) | [Telegram Bot](https://t.me/DG2welcomebot) | [Web Preview](https://deskgram2.com/web-preview)
## 交互式 Web Preview

[![Interactive Demo](https://img.shields.io/badge/DEMO-Try_in_Browser-brightgreen?style=for-the-badge&logo=google-chrome)](https://deskgram2.com/app-demo/tasks)

在浏览器中体验这个模块: [打开 Web Preview](https://deskgram2.com/app-demo/tasks)

任务计划器: [打开调度器](https://deskgram2.com/web-preview?path=%2Fapp-demo%2Fscheduler)



## 模块简介

| 参数 | 内容 |
|---|---|
| 核心任务 | 集中监控 Telegram 自动化任务 |
| 适用场景 | 多模块并行操作和日常执行控制 |
| 核心动作 | 筛选、状态查看、任务检查、快速处理 |
| 关键价值 | 用一个看板观察运行中和已完成的流程 |
| 关联模块 | 神经评论、私信群发、账号面板 |

## 模块能力

- 展示运行中和已完成任务的统一表格；
- 快速查看状态和执行结果；
- 发现错误和卡住的流程；
- 支持筛选和任务级操作；
- 把日常监控集中在一个位置。

## 快速开始

1. 启动自动化流程后打开任务面板。
2. 查看运行中和已完成任务的总体情况。
3. 用筛选功能聚焦需要关注的任务。
4. 在需要时打开历史或停止异常流程。

## 这里最适合监控哪些执行场景

- [神经评论](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram-zh)，当你需要看 AI 评论活动和错误时；
- [私信群发](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-zh)，当触达流程跨多个账号并行运行时；
- [受众收集](https://github.com/Deskgram-2/telegram-audience-parser-deskgram-zh)，当多个采集任务同时进行时；
- [邀请模块](https://github.com/Deskgram-2/telegram-invite-tool-deskgram-zh)，当邀请进度和失败情况需要被持续看到时；
- [加群模块](https://github.com/Deskgram-2/telegram-join-groups-deskgram-zh)，当账号活跃流程也需要统一运维监控时。

## 适合在什么情况下使用

- 当多个模块同时运行；
- 当操作者需要知道当前到底发生了什么；
- 当错误和卡住的流程必须尽快被看到；
- 当日常执行依赖持续的任务可见性。

## 相比手动监控更方便的地方

| 手动方式 | Deskgram 2 任务管理器 |
|---|---|
| 状态分散在不同窗口里 | 提供统一看板和任务表格 |
| 难以估计当前工作负载 | 集中展示整体运行情况 |
| 历史与活动流程割裂 | 监控被集中起来 |
| 问题任务定位更慢 | 内置任务级快速控制 |
| 错误容易被忽略 | 状态可见性更高 |

## 适用场景

- 当 [受众收集](https://github.com/Deskgram-2/telegram-audience-parser-deskgram-zh)、[私信群发](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-zh) 和 [邀请模块](https://github.com/Deskgram-2/telegram-invite-tool-deskgram-zh) 同时运行时，集中控制并行活动；
- 监控像 [神经评论](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram-zh) 这样的 AI 模块，方便更快发现错误；
- 在基础设施准备完成后，持续观察执行层的运行状态；
- 为团队提供一个统一运维面板，在多个 Deskgram 2 工作流并行时减少混乱。

## 该选哪个：任务管理器还是账号面板

| 如果你的目标是 | 更适合哪个 |
|---|---|
| 看到当前有哪些流程在运行、状态如何 | `任务管理器` |
| 为新场景准备账号子集 | [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh) |
| 快速停止异常流程并查看历史 | `任务管理器` |
| 管理账号基础而不是执行状态 | [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh) |

## 相关仓库

- [Deskgram 2 中文总览](https://github.com/Deskgram-2/deskgram-2-telegram-automation-zh)
- [神经评论](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram-zh)
- [私信群发](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-zh)
- [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh)
- [受众收集](https://github.com/Deskgram-2/telegram-audience-parser-deskgram-zh)
- [邀请模块](https://github.com/Deskgram-2/telegram-invite-tool-deskgram-zh)
- [加群模块](https://github.com/Deskgram-2/telegram-join-groups-deskgram-zh)

## FAQ

### 如果模块自己已经显示进度，为什么还需要任务面板？

因为这里给的是跨模块的统一运行视图，不需要在多个窗口之间来回切换。

### 它最适合什么场景？

最适合多个 Telegram 场景并行执行的时候。
