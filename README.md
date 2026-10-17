# Chengyun · Ev1ldore

构建可追溯、可恢复、有人类审核边界的 AI 应用：RAG、Agent 工作流与面向实际业务的 LLM 产品。

![GitHub Profile](https://img.shields.io/badge/GitHub-Ev1ldore-181717?logo=github&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-Applied%20AI%20%7C%20RAG%20%7C%20Agents-2563EB)

## 特性

- 基于文档证据构建问答与检索：混合检索、重排、引用与冲突处理。
- 构建可恢复的 Agent 工作流：持久化状态、人工审核、失败处理与执行追踪。
- 交付可运行的 AI 工作台：模型网关、后台任务、导出与可复核结果。
- 清楚说明验证范围：区分本地演示、模拟集成与真实服务验证。

## 环境要求

- 各公开项目有各自的运行环境与依赖说明。
- Python 项目通常要求 Python 3.11+；前端项目的 Node.js 版本以对应仓库为准。

## 安装

这是个人主页仓库，不提供统一安装包。请选择具体项目并按其 README 安装：

- [Customer Profile](https://github.com/Ev1ldore/customer-profile)
- [Amazon After-Sales Agent](https://github.com/Ev1ldore/amazon-after-sales-agent)
- [Content Studio](https://github.com/Ev1ldore/content-studio)
- [Domain Knowledge Assistant](https://github.com/Ev1ldore/domain-knowledge-assistant)
- [LLM Video Script Generator](https://github.com/Ev1ldore/llm-video-script-generator)

## 快速开始

```bash
git clone https://github.com/Ev1ldore/customer-profile.git
cd customer-profile
```

随后按该项目 README 中的环境配置、安装与启动步骤运行。

## 配置

| 参数 | 说明 | 默认值 |
| --- | --- | --- |
| 项目运行时 | Python、Node.js 或其他运行时，按具体项目选择 | 以项目 README 为准 |
| 模型服务配置 | API 地址、密钥与模型名 | 以项目 `.env.example` 为准 |
| 外部集成配置 | 数据源或第三方服务的凭据与开关 | 默认不提供真实凭据 |

## 测试

每个项目分别提供验证命令与已验证范围。提交前请执行该项目 README 或 CI 中列出的测试、静态检查和必要的本地冒烟验证。

## 当前项目

### WeCom Personal Reply Agent（私有本地 MVP）

正在构建一个本地优先的企微个人消息助手：从已验证的桌面单聊读取新消息，生成 LLM 回复，并在用户明确控制下发送。它保留企微原始显示时间，过滤自身消息，用 SQLite 持久化去重与发送结果，并默认以 dry-run 启动。该实现仍为私有项目，真实交互流程持续验证中。

## 贡献

欢迎在具体公开项目中提交 Issue 或 Pull Request。提交前请阅读该项目的贡献说明；本主页仓库目前没有独立的 `CONTRIBUTING.md`。

## License

本个人主页仓库目前未声明独立许可证；各项目的许可信息以各自仓库为准。

[Writing & experiments](https://modelwithin.cloud) · [Public projects](https://github.com/Ev1ldore?tab=repositories)
