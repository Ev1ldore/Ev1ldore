<div align="center">

# Chengyun

**大模型应用开发 · RAG · Agent 工作流**

把知识检索、模型能力与人工审核接入具体业务。  
关注可追溯的回答、可恢复的任务，以及可复核的交付。

[![Blog — Model Within](https://img.shields.io/badge/Blog-Model%20Within-2563EB?style=for-the-badge&logo=wordpress&logoColor=white)](https://modelwithin.cloud)
[![GitHub — Ev1ldore](https://img.shields.io/badge/GitHub-Ev1ldore-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ev1ldore?tab=repositories)

[阅读博客 ↗](https://modelwithin.cloud) · [浏览仓库 ↗](https://github.com/Ev1ldore?tab=repositories)

</div>

## 精选项目

| 项目 | 解决的问题 | 主要技术 |
| :--- | :--- | :--- |
| [**知识问答助手**](https://github.com/Ev1ldore/domain-knowledge-assistant) | 从自有文档中检索答案，关联来源证据，呈现资料缺失与冲突。 | Python · FastAPI · 混合检索 · SQLite |
| [**Amazon 售后协作助手**](https://github.com/Ev1ldore/amazon-after-sales-agent) | 串联工单、订单核查、政策检索和回复草稿，交由人工审核。 | LangGraph · FastAPI · Vue 3 |
| [**Content Studio**](https://github.com/Ev1ldore/content-studio) | 从资料与选题走到文章、图文审核和内容包导出。 | LangGraph · React · PostgreSQL |
| [**客户画像工作台**](https://github.com/Ev1ldore/customer-profile) | 将分散资料整理为结构化报告，支持来源定位、人工修订与联网复核。 | Python · SQLite · JavaScript |

<details>
<summary>项目状态与验证边界</summary>

- **知识问答助手：** 面向小型知识库、单进程部署；规模与并发性能未验证，模型审核效果需按领域评估。
- **Amazon 售后协作助手：** 订单接入通过 fixture 与模拟响应验证；真实卖家、MySQL/Milvus 路径仍需独立验证，不自动发送消息或退款。
- **Content Studio：** 提供本地 Mock 演示；Mock / 文字 API 模式图片为固定样例，独立进程模式使用模板渲染，内容由用户手动发布。
- **客户画像工作台：** 面向本地使用，演示资料为合成数据，证据支持度采用规则计算。

具体实现与验收记录见各项目仓库。

</details>

## 关注方向

**RAG 与证据追溯** · **Agent 状态与恢复** · **人工审核与版本管理** · **离线评测与执行轨迹**

> 让答案有来源，让失败有状态，让关键决定由人确认。
