# 你好，我是 Nancy

我正在准备软件工程实习，目前重点关注 **全栈 AI 应用开发**，尤其是 Spring AI、Agent、RAG 知识库和前端交互体验。

我希望自己的 GitHub 不只是放一个能跑的 Demo，而是持续记录一个项目从「功能可用」到「工程化、可维护、可展示」的迭代过程。

## 最近在做

| 方向 | 我正在提升的能力 |
| --- | --- |
| 后端开发 | Spring Boot 服务设计、REST API、MyBatis、SSE 实时推送 |
| AI 应用 | Agent Loop、手动 Tool Calling、多模型切换、RAG 检索 |
| 前端开发 | React、TypeScript、Ant Design、聊天界面、加载/错误/空状态 |
| 工程实践 | README 文档、环境变量配置、lint/build 验证、清晰提交记录 |

## 代表项目

### [ThinkLoop - AI Agent Assistant](https://github.com/nancy050416/my-project)

这是一个基于 **Spring AI + React** 的 AI Agent 应用实践项目，用来探索如何把大模型能力接入一个可控制、可观测、可扩展的后端系统。

项目不是只做一个普通聊天框，而是围绕「大模型对话 + 工具调用 + RAG 知识库 + 实时执行反馈」构建。

**项目包含：**

- Agent Think-Execute Loop，用于处理多步骤任务
- 手动接管 Tool Calling 生命周期，便于持久化、观测和扩展
- Markdown 文档上传、解析、切片与向量化
- PostgreSQL + pgvector 实现知识库相似度检索
- SSE 实时推送 Agent 的规划、思考、执行和完成状态
- React + TypeScript 前端，支持智能体、会话和知识库管理
- 使用 Vite 环境变量配置前端 API / SSE 地址，避免硬编码

**技术栈：**

Java 17、Spring Boot、Spring AI、MyBatis、PostgreSQL、pgvector、React、TypeScript、Vite、Ant Design

## 最近更新

- 重构前端运行时配置，将 API 和 SSE 地址抽离为环境变量
- 优化新对话入口页，让 Agent / RAG / 实时反馈的产品逻辑更清晰
- 拆分 React Context 和 Hook，修复 lint 中的 Fast Refresh 结构问题
- 重写项目 README，让架构、技术栈和本地运行方式更容易阅读
- 使用 `npm run build` 和 `npm run lint` 验证前端质量

## 接下来计划

- 增加 RAG 检索评测样例，对比 Top-K 召回效果
- 尝试关键词检索 + 向量检索的混合召回
- 完善工具调用失败后的重试和降级逻辑
- 为 SSE 增加心跳和更完整的异常恢复
- 补充项目截图、架构图和部署说明

## 联系我

- GitHub: [nancy050416](https://github.com/nancy050416)
- Email: 2167920027@qq.com

