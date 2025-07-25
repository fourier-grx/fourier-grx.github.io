---
layout: default
title: Fourier-GRX-GR2 SDK
nav_order: 1
has_children: false
toc: true          # 启用目录
toc_min_header: 2  # 最小显示标题层级（如 H2）
toc_max_header: 3  # 最大显示标题层级（如 H3）
---

# 欢迎来到 Fourier-GRX-GR2 SDK 开发文档

> ⚠️ **注意**
>
> - 目前 `fourier-grx-GR2` 仅针对 GR2 **强化学习**相关内容做支持，其他方面的开发支持后续计划更换新的软件支持平台（暂未发布）。
> - 新的开发平台计划发布于 2025 年末。届时，fourier-grx 接口将保留但不做频繁更新。新的开发接口将会在最大程度上兼容现有的 `fourier-grx-GR2` 接口使用方法，并建议用户迁移到新的接口。

## 介绍

Fourier-GRX-GR2 SDK 是傅利叶智能提供的一个软件开发工具包，
提供了一套 API 用于安装、配置、控制傅利叶智能的 GR2 机器人产品的应用程序。

该 SDK 设计简洁易用，提供高级接口来控制机器人运动并读取传感器数据。
SDK 目前主要支持 Python 语言二次开发使用。

## 开始使用

[快速开始](/fourier-grx-GR2/docs/quickstart) 是开始使用 Fourier-GRX-GR2 SDK 库的推荐方式。
这份分步指南将帮助您安装所需库文件并运行简单程序来控制机器人。

[示例代码](/fourier-grx-GR2/docs/examples) 演示了 SDK 库的使用方法，可作为您开发应用程序的参考程序。

[参考指南](/fourier-grx-GR2/docs/reference) 包含了 SDK 库的详细 API 文档，可作为您开发应用程序的参考文档。

[模型训练](/fourier-grx-GR2/docs/training) 包含了如何进行机器人强化学习模型训练的说明。

[常用操作](/fourier-grx-GR2/docs/usage) 包含了一些常用操作的说明，包括但不限于固件安装方法，机器人校准方法，以及操作模式的切换等。

[常见问题](/fourier-grx-GR2/docs/faq) 包含了一些常见问题的解答，可帮助您解决一些常见问题。如果您有遇到更多问题，也欢迎[贡献](/fourier-grx-GR2/docs/contributing)您的一份力量，帮助我们改进。

[固件更新](/fourier-grx-GR2/docs/update) 包含了发布的新固件以及介绍如何更新固件。

## 支持平台与版本

| 系统环境             | Python 环境   | 已测试 | 测试通过 |
|------------------|-------------|-----|------|
| Ubuntu 22.04 LTS | Python 3.11 | ✅   | ✅    |
| Windows          | Python 3.11 |     |      |
| MacOS            | Python 3.11 |     |      |

> **说明**:
>
> Fourier-GRX-GR2 SDK 具备 User 和 Developer 两类不同层级的接口。
> - User 接口基于 [Zenoh](https://zenoh.io) 协议开发
> - Developer 接口基于 Python 库开发。
>
> 基于 [Zenoh](https://zenoh.io) 协议调用 User 接口，无明确平台和语言限制，但仍推荐在 Ubuntu 系统上进行开发。

## 日志更新

请查看 [日志更新](/fourier-grx-GR2/docs/changelog) 以获取最新版本文档的更新内容。

## 贡献指南

请阅读我们的[贡献指南](/fourier-grx-GR2/docs/contributing)以获取更多信