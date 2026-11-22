<div align="center">

# Chengyun

**大模型应用开发 · RAG · Agent 工作流**

让模型走进业务，也让每一步经得起追问。  
围绕知识、流程与人，构建有据可查、有序可循的 AI 应用。

[![Blog — Model Within](https://img.shields.io/badge/Blog-Model%20Within-2563EB?style=for-the-badge&logo=wordpress&logoColor=white)](https://modelwithin.cloud)
[![GitHub — Ev1ldore](https://img.shields.io/badge/GitHub-Ev1ldore-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ev1ldore?tab=repositories)

**简体中文** · [English](README.en.md)

</div>

## 项目

### 01
**[Domain Knowledge Assistant · 知识问答助手 ↗](https://github.com/Ev1ldore/domain-knowledge-assistant)**

把“答案是什么”推进到“依据在哪里”。围绕自有文档构建问答应用，结合混合检索、可选重排序与逐结论证据关联，呈现资料缺失、来源冲突和人工复核入口。

`Python` `FastAPI` `SQLite` `Hybrid Retrieval`

### 02
**[Amazon After-Sales Agent · 售后协作助手 ↗](https://github.com/Ev1ldore/amazon-after-sales-agent)**

让客服带着订单事实和政策依据处理工单。通过 LangGraph 串联核查、检索、建议与回复草稿，以版本管理、执行轨迹和人工审核支撑可追溯的售后协作。

`Python` `LangGraph` `FastAPI` `Vue 3`

### 03
**[Content Studio · 图文内容工作台 ↗](https://github.com/Ev1ldore/content-studio)**

从一份资料走到一份可审核的内容包。将选题、文章编辑、图文制作与导出串成工作流，通过版本绑定的人工审核、检查点恢复和单页重做，支持反复打磨内容。

`React` `FastAPI` `LangGraph` `PostgreSQL`

### 04
**[Customer Profile · 客户画像工作台 ↗](https://github.com/Ev1ldore/customer-profile)**

把散落在文档与沟通记录中的客户信息整理成可复核的报告。连接结构化字段与原始证据，保留资料分歧和人工修订，并提供联网核实与导出流程。

`Python` `SQLite` `JSON Schema` `JavaScript`

<details>
<summary>项目状态与验证边界</summary>

- **知识问答助手：** 面向小型知识库、单进程部署；规模与并发性能未验证，模型审核效果需按领域评估。
- **售后协作助手：** 订单接入通过 fixture 与模拟响应验证；真实卖家及 MySQL/Milvus 路径仍需独立验证，不自动发送消息或退款。
- **内容工作台：** 提供本地 Mock 演示；Mock / 文字 API 模式图片为固定样例，独立进程模式使用模板渲染，内容由用户手动发布。
- **客户画像：** 面向本地使用，演示资料为合成数据，证据支持度采用规则计算。

具体实现与验收记录见各项目仓库。

</details>

## 工程关注

**证据追溯** / **状态与恢复** / **人工审核** / **评测与观测**

我关心模型生成结果之后的工程问题：依据如何保留，状态如何流转，失败如何处理，最终由谁确认。

---

[**Model Within ↗**](https://modelwithin.cloud) · 我的技术博客与实验记录
