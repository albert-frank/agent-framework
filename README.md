# 收录主流 agent 框架

以下是汇总的 **国内外主流 Agent 框架对比表**，按 GitHub Stars 降序排列，方便不同技术栈的开发者快速选型查阅：

---

## 国内外主流 Agent 框架汇总对比表（2026-08）

|  排名 | 框架                                  | Stars | 核心语言                    |   地区  | 出品方                           | 类型       | 核心定位                                                |
| :-: | :---------------------------------- | :---: | :---------------------- | :---: | :---------------------------- | :------- | :-------------------------------------------------- |
|  1  | **AutoGPT**                         |  186k | Python                  |   海外  | 社区                            | SDK / 应用 | 自主任务循环 Agent，最早的开源自主 Agent 鼻祖                       |
|  2  | **n8n**                             |  160k | TypeScript              |   海外  | n8n GmbH                      | 低代码平台    | 工作流自动化 + AI 能力集成                                    |
|  3  | **Langflow**                        |  152k | Python                  |   海外  | DataStax                      | 低代码平台    | LangChain 可视化拖拽编辑器                                  |
|  4  | **Dify**                            |  149k | TypeScript / Python     |   国内  | Dify.AI                       | 低代码平台    | 可视化 Agent 工作流 + RAG，一键 API 发布                       |
|  5  | **LangChain**                       |  144k | Python / JS             |   海外  | 社区                            | SDK      | 通用 LLM/Agent 生态，链、工具、记忆、向量库                         |
|  6  | **Browser-use**                     |  93k  | Python                  |   海外  | 社区                            | SDK      | Web 浏览器自动化交互，模拟人类进行网页操作                             |
|  7  | **RAGFlow**                         |  77k  | Python / TS             |   国内  | 社区                            | 平台       | 深度文档解析 RAG + Agent，PDF/表格复杂文档                       |
|  8  | **DeerFlow**                        |  75k  | Python                  |   国内  | 字节跳动                          | SDK      | 长周期 SuperAgent，反思闭环、沙箱、子 Agent                      |
|  9  | **MetaGPT**                         |  70k  | Python                  |   国内  | 深度赋智                          | SDK      | 多 Agent 模拟软件公司（产品/开发/测试）                            |
|  10 | **AutoGen**                         |  60k  | Python / C#             |   海外  | Microsoft                     | SDK      | 多 Agent 对话编排（已合并进入 MAF 维护模式）                        |
|  11 | **CrewAI**                          |  57k  | Python                  |   海外  | CrewAI Inc                    | SDK      | 角色驱动多 Agent：Agent-Task-Crew 模型                      |
|  12 | **OpenManus**                       |  56k  | Python                  |   国内  | FoundationAgents / MetaGPT 团队 | SDK / 应用 | Manus 开源替代，通用自主 Agent                               |
|  13 | **Flowise**                         |  55k  | TypeScript              |   海外  | FlowiseAI                     | 低代码平台    | 可视化拖拽构建 Agent                                       |
|  14 | **LlamaIndex**                      |  52k  | Python / TS             |   海外  | LlamaIndex                    | SDK      | 面向 RAG 的 Agent，数据连接与检索能力极强                          |
|  15 | **OpenHands**                       |  44k  | Python                  |   海外  | All-Hands-AI                  | SDK / 应用 | AI 软件工程师                                            |
|  16 | **Agno**                            |  41k  | Python                  |   海外  | 社区                            | SDK      | 极简高性能 Agent                                         |
|  17 | **LangGraph**                       |  40k  | Python / TS             |   海外  | LangChain                     | SDK      | 有状态图状态机 Agent，checkpoint、人机介入、循环分支                  |
|  18 | **ChatDev**                         |  34k  | Python                  |   国内  | 清华 OpenBMB                    | SDK      | 虚拟软件公司协作开发                                          |
|  19 | **DSPy**                            |  33k  | Python                  |   海外  | Stanford NLP                  | SDK      | 自动 Prompt 编译优化                                      |
|  20 | **FastGPT**                         |  29k  | TS / Python             |   国内  | 社区                            | 平台       | 知识库 RAG + 简易 Agent，国内中小企业 RAG                       |
|  21 | **smolagents**                      |  29k  | Python                  |   海外  | Hugging Face                  | SDK      | 极简代码优先的轻量级 Code Agent                               |
|  22 | **OpenAI Agents SDK**               |  29k  | Python / TS             |   海外  | OpenAI                        | SDK      | OpenAI 官方生态 SDK，Agent 切换 handoff、tracing            |
|  23 | **Semantic Kernel**                 |  28k  | C# / Python / Java      |   海外  | Microsoft                     | SDK      | 企业级中间件（目前处于维护模式）                                    |
|  24 | **Microsoft Agent Framework (MAF)** |  28k  | Python / C#             |   海外  | Microsoft                     | SDK      | 微软新版统一框架，合并 AutoGen + Semantic Kernel               |
|  25 | **AgentScope**                      |  28k  | Python / Java                  |   国内  | 阿里巴巴                          | SDK      | 大规模多 Agent 仿真，分布式执行                                 |
|  26 | **Mastra**                          |  27k  | TypeScript              |   海外  | Mastra AI                     | SDK      | TypeScript 原生全栈 Agent，前端 Node.js 一体化                |
|  27 | **Vercel AI SDK**                   |  26k  | TypeScript              |   海外  | Vercel                        | SDK      | 前端 UI 集成                                            |
|  28 | **BabyAGI**                         |  22k  | Python                  |   海外  | 社区                            | SDK      | 极简任务驱动                                              |
|  29 | **Rasa**                            |  21k  | Python                  |   海外  | Rasa                          | 平台       | 企业级对话管理                                             |
|  30 | **Google ADK**                      |  21k  | Python / Go / Java / TS |   海外  | Google                        | SDK      | Gemini / Vertex 官方套件，云原生部署 + A2A 协议                 |
|  31 | **DB-GPT**                          |  20k  | Python                  |   国内  | 社区                            | SDK      | 数据分析与数据库交互（Text-to-SQL、数据可视化）                       |
|  32 | **Pydantic AI**                     |  19k  | Python                  |   海外  | Pydantic                      | SDK      | 类型安全 Agent，工具入参出参强校验，DI 依赖注入                        |
|  33 | **SuperAGI**                        |  18k  | Python                  |   海外  | 社区                            | 平台       | 企业级 Agent 管理平台                                      |
|  34 | **Qwen-Agent**                      |  17k  | Python                  |   国内  | 阿里云                           | SDK      | 通义千问生态                                              |
|  35 | **Letta (MemGPT)**                  |  16k  | Python / TS             |   海外  | Letta AI                      | SDK      | OS 级长期记忆                                            |
|  36 | **Botpress**                        |  15k  | TypeScript              |   海外  | Botpress                      | 平台       | 对话式 AI 平台                                           |
|  37 | **ERNIE-Bot**                       |  13k  | Python                  |   国内  | 百度                            | SDK      | 文心一言生态                                              |
|  38 | **LangChain4j**                     |  13k  | Java                |   海外  | 社区 (Dawid Kubrak)             | SDK      | Java 原生 LLM 框架，框架中立，支持 20+ LLM 和 30+ 向量存储           |
|  39 | **Eino**                            |  12k  | Go                      |   国内  | 字节跳动                          | SDK      | Go 原生 LLM 框架，填补 Go 后端生态空白                           |
|  40 | **Spring AI Alibaba**               |  10k  | Java                |   国内  | 阿里团队                          | SDK      | 阿里基于 Spring AI 的扩展，面向国内开发者，中文友好，阿里云深度集成             |
|  41 | **Spring AI**                       |   9k  | Java                |   海外  | VMware / Spring team          | SDK      | Spring 生态官方 AI 抽象层，与 Spring Boot 深度集成               |
|  42 | **XAgent**                          |   9k  | Python                  |   国内  | 清华 + OpenBMB                  | SDK      | 自主智能体，双层图规划机制，复杂长流程任务                               |
|  43 | **LangBot**                         |   8k  | Python                  |   国内  | 社区                            | SDK      | 多平台机器人                                              |
|  44 | **Claude Agent SDK**                |   7k  | Python / TS             |   海外  | Anthropic                     | SDK      | Claude 深度优化                                         |
|  45 | **AG2**                             |   -   | Python                  |   海外  | 社区                            | SDK      | AutoGen 继任者                                         |
|  46 | **Deep Agents**                     |   -   | Python                  |   海外  | 社区                            | SDK      | 深度 Agent 框架                                         |
|  47 | **Strands Agents SDK**              |   -   | Python                  |   海外  | 社区                            | SDK      | Agent SDK                                           |
|  48 | **Atomic Agents**                   |   -   | Python                  |   海外  | 社区                            | SDK      | 原子化 Agent 构建                                        |
|  49 | **Camel-AI**                        |   -   | Python                  |   海外  | 社区                            | SDK      | 多 Agent 协作框架                                        |
|  50 | **ModelScope-Agent**                |   -   | Python                  |   国内  | 阿里达摩院                         | SDK      | 基于魔搭生态，多模态 Tool-use                                 |
|  51 | **Coze**                            |   -   | Python / Go / TS        | 国内/海外 | 字节跳动                          | 平台       | AI 应用开发平台（海外版 Coze / 国内版扣子），低代码 Bot 构建 + 插件生态 + 工作流 |


---

### 按核心开发语言统计

| 核心语言                    | 框架数量 |  占比  | 代表框架                                                |
| :---------------------- | :--: | :--: | :-------------------------------------------------- |
| **Python**              |  36  | ~71% | AutoGPT、LangChain、MetaGPT、CrewAI、OpenManus 等        |
| **TypeScript**          |   6  | ~12% | n8n、Flowise、Mastra、Botpress、Vercel AI SDK 等         |
| **Python + TypeScript** |   5  | ~10% | Dify、LangGraph、LlamaIndex、OpenAI Agents SDK 等       |
| **Java**                |   3  |  ~6% | LangChain4j、Spring AI、Spring AI Alibaba |
| **Go**                  |   1  |  ~2% | Eino（字节跳动）                                          |
| **C# / Java**           |   1  |  ~2% | Semantic Kernel（Microsoft）                          |

---

### 选型速查建议

| 场景 | 推荐框架 | 理由 |
|:---|:---|:---|
| **快速原型 / 角色扮演** | CrewAI、MetaGPT、ChatDev | API 简单，角色驱动，上手极快 |
| **生产级复杂工作流** | LangGraph、Dify | 有状态图管理、checkpoint、可视化编排 |
| **RAG + 知识库** | LlamaIndex、RAGFlow、FastGPT | 数据连接与文档解析能力极强 |
| **浏览器自动化** | Browser-use、OpenManus | 专注 Web 交互，模拟人类操作 |
| **前端/全栈 TS 项目** | Mastra、Vercel AI SDK | TypeScript 原生，与 Node.js 生态无缝集成 |
| **Go 后端微服务** | Eino | 唯一 Go 语言框架，性能优异 |
| **企业级 .NET 生态** | Semantic Kernel / MAF | Azure 深度集成，强类型安全 |
| **长周期研究任务** | DeerFlow、OpenHands | 反思闭环、沙箱执行、AI 软件工程 |
| **低代码/无代码** | n8n、Flowise、Langflow | 拖拽搭建，非技术人员友好 |
| **类型安全 / 减少幻觉** | Pydantic AI | 入参出参强校验，生产代码质量高 |
