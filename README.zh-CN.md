# SandBase Lab 项目指南

**连接真实世界的开源 Agent 实验场，从原型走向生产。**

[English](README.md) · [项目标准](docs/project-standard.md) · [贡献指南](CONTRIBUTING.md)

我们组合模型、API 与 Sandbox，快速做出可见、可重复的真实效果。每个 Agent 应用都是一个独立仓库，用户可以体验、复现、二次开发，并验证是否适合自己的生产环境。

## 从哪里开始

| 目标 | 入口 |
| --- | --- |
| 了解 Lab 和使用路径 | [入门指南](docs/getting-started.md) |
| 找可运行项目 | [项目目录](README.md#project-directory) |
| 提议新实验 | [提交提案](https://github.com/sandbase-lab/lab-guide/issues/new?template=lab-proposal.md) |
| 发布独立项目 | [项目标准](docs/project-standard.md)与 [README 模板](docs/project-readme-template.md) |
| 从原型走向生产 | [生产化检查清单](docs/production-checklist.md) |

## 当前状态

组织和指南已经发布，目前尚无可运行的 Agent 项目。研究报告、内容创作、数据分析是候选方向，尚未实现。项目验证完成后再加入公开目录。

## 项目演进

实验验证 → 可复现原型 → 效果评估 → 部署与运行。

每个仓库独立维护代码、依赖、版本、许可证和部署说明，并明确标记“实验 / 可试用 / 生产就绪”。生产就绪必须对应具体运行范围和验证证据。

## 参与和费用

无需加入组织即可提交 Issue 或 PR。欢迎贡献场景、可复现代码、失败样例及生产实践。

本指南采用 [Apache-2.0](LICENSE)。各项目单独说明许可证；托管服务和第三方 API 的使用费用不包含在开源授权中。项目应提供 mock 或 fixtures，帮助用户先了解流程。

由 [SandBase](https://www.sandbase.ai/) 发起和维护。
