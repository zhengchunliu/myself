# 刘正春

**AI 应用工程师 / AI Agent 开发工程师**

手机：18945018938 ｜ 邮箱：[lzcmac@163.com](mailto:lzcmac@163.com) ｜ 现居：深圳

---

## 个人优势

- **8 年算法与工程化经验、3 年大模型应用一线落地经验**。从推荐/搜索算法工程师成长为企业级 Agent 平台核心开发，具备算法理解、后端服务到 Agent 系统抽象的完整能力链路。
- **企业级 Agent 系统端到端设计与落地能力**。独立负责过 SuperAgent 调度、Agent Runtime、A2A 协议、多轮协商状态机、人机混合调度、Server-Driven UI、事件驱动架构等核心模块，把 Agent 从 Demo 推进到可路由、可降级、可恢复、可观测的生产系统。
- **协议级抽象与架构演进能力**。习惯把业务问题拆解为协议、状态机和可复用模块，而非堆 API；关注路由降级、双轨兜底、子模块解耦、熔断回流等生产级工程细节。
- **完整 RAG 与垂直问答经验**。覆盖意图识别、实体抽取、文档切片、向量召回、重排和领域微调全链路，落地过体育领域智能搜索与问答系统。

---

## 专业技能

- **大模型应用**：Prompt Engineering、System Prompt 设计、Function Calling、ReAct、Agent Runtime、Tool Registry、长短期记忆、流式输出、卡片化交互
- **Agent 工程**：Multi-Agent Orchestration、SuperAgent 路由、A2A 协议、多轮协商状态机、DAG 任务编排、Hybrid Dispatch、Service Agent 注册与熔断、Server-Driven UI、事件驱动架构
- **RAG 与搜索问答**：知识库构建、文档切片、Embedding、向量检索、语义召回、重排、意图识别、实体抽取、领域问答优化、模型微调
- **后端与架构**：Python、FastAPI、Java、Spring Boot、SQLAlchemy、MySQL、Redis、SSE、JWT、asyncio、Docker、Jenkins、Repository 模式
- **算法与数据**：Transformer / BERT / GPT 原理、推荐召回排序（DSSM、Wide&Deep、DeepFM、DIN）、Graph Embedding、Spark、Hadoop、Hive

---

## 工作经历

### 滴灌通科技（深圳）有限公司 ｜ 资深 AI 应用开发工程师 ｜ 2025.04 - 至今

- 主导集团 AI 应用与 Agent 平台的技术规划、架构设计与工程落地，面向 HR、任务调度、数字分身、管理驾驶舱等场景构建企业级智能体系统。
- 主导设计并开发 **滴灌通企业 Micro Agent OS 平台**，将组织内的人、数字分身、Service Agent、系统能力统一抽象为可调度对象，由 SuperAgent 按目标驱动完成理解、路由、拆解、协商、派发、执行与结果回流的全链路闭环。
- 端到端负责 SuperAgent 调度、Agent Runtime、A2A 协议、Hybrid Dispatch 人机混合调度、A2UI Server-Driven UI、Domain EventBus 等核心模块的建设。
- 推动 Agent 工程化与稳定性体系建设：围绕路由降级、双轨 Runtime 兜底、流式重复检测、工具调用卡片绑定、外部 Agent 熔断等问题落地生产级机制。

### 北京新爱体育传媒科技有限公司（爱奇艺体育）｜ 大模型应用开发工程师 / 推荐算法工程师 ｜ 2020.08 - 2024.12

- 从 0 到 1 搭建公司大模型应用技术栈，落地垂类知识问答、AI 内容生成、文章翻译重写、智能搜索等核心场景，将 LLM 能力接入内容生产、用户服务和运营提效流程。
- 带队建设基于 **RAG** 的体育领域智能搜索与问答系统，通过 Prompt 优化、意图识别、实体抽取、向量召回与重排、领域微调，显著提升垂域问答准确率。
- 独立搭建首页信息流与竖屏联播推荐系统，覆盖多路召回与 DSSM、Wide&Deep、DeepFM、DIN 排序模型，持续优化 CTR、停留时长与次日留存等核心指标。

### 快手 ｜ 算法工程师 ｜ 2020.01 - 2020.07

- 参与快手 APP 同城页短视频推荐算法研发与策略优化，负责推荐策略迭代、特征分析与 AB 实验效果评估。

### 阿里本地生活服务公司（饿了么）｜ 算法工程师 ｜ 2018.04 - 2020.01

- 负责蜂鸟众包智能配送调度核心算法研发与策略优化，参与配送路径优化、运力调度等核心项目，多次获得部门优秀项目奖。

---

## 重点项目

### 滴灌通企业 Micro Agent OS 平台 ｜ Agent 系统核心开发 / 架构设计 ｜ 2025.04 - 至今

**项目定位**：面向集团内部 HR 服务、任务派发、工分激励、员工协作和管理驾驶舱等场景，构建企业级 Agent 调度平台。平台将人、数字分身、Service Agent、系统能力统一抽象为可调度对象，使用户通过单一对话入口表达目标后，由系统完成理解、路由、拆解、协商、执行与结果回流。

**技术栈**：Python、FastAPI、AgentScope ReActAgent、OpenAI 兼容 LLM、Function Calling、A2A / A2UI 协议、SQLAlchemy、MySQL、asyncio、SSE、React 18、TypeScript、Docker、Jenkins。

- **设计企业级 Agent 调度架构**：将平台拆分为 SuperAgent 调度层、Agent Runtime 执行层、Tool / Skill 能力层、A2A 协作层、Hybrid Dispatch 编排层和 Domain EventBus 事件层，使 Agent 从"问答助手"升级为可驱动任务、工单、外部服务和数字分身协作的业务执行系统。
- **落地 SuperAgent 三层退化路由**：设计 `Guard → LLM Router → Keyword Fallback` 路由机制，将 System Agent、User Agent、Service Agent 纳入统一候选池；在 LLM 超时、低置信和路由不明确时自动降级或返回澄清卡片，提升复杂业务入口的稳定性。
- **封装 Agent Runtime 与 Agent Harness**：基于 AgentScope ReActAgent 统一模型初始化、记忆桥接、工具上下文和 SSE 增量解析；将 `thinking / tool_use / tool_result / text chunk` 转换为前端卡片化协议，解决多处对话链路重复实现、工具结果错位和流式输出不可控问题。
- **实现 A2A 数字分身协作能力**：落地 Agent Card 动态生成、能力发现、跨工作室 Session、Auto Responder 与多轮协商状态机，使员工数字分身能够参与"任务邀约 - 讨论 - 接受/拒绝"的业务闭环。
- **设计 Hybrid Dispatch 人机混合调度链路**：由 LLM Planner 将复杂目标拆解为 DAG，再按 Service Agent 精确匹配、语义匹配、数字分身协商、真人技能匹配、人工指定五级优先级选择执行者，并输出匹配分数、预估耗时和决策原因，支持前端可解释预览。
- **建设生产级执行与实时回流机制**：实现 PlanExecutor 拓扑调度、JobExecutor 同步/异步调用、Service Agent 回调、CircuitBreaker 熔断、结果聚合和失败接管入口；通过 asyncio Domain EventBus + SSE 单通道向前端实时推送任务、协商、调度、工分和 War Room 建议等事件。
- **推动能力扩展与架构演进**：设计 `Skill = Prompt + Tools + Dynamic Context + Suggestions` 的自包含能力模型，降低新增 Agent 能力成本；推进 Studio Factory 子模块化和 PyMySQL 到 SQLAlchemy Repository 的渐进迁移，使平台在快速迭代中保持模块边界清晰。

**项目价值**：沉淀出可复用的 Agent 路由、工具调用、协议协作、任务编排、事件回流和工程兜底能力，为企业知识问答、流程自动化、管理驾驶舱与跨系统 Agent 集成提供统一技术底座。

### 爱奇艺体育 APP 首页信息流推荐服务 ｜ 推荐算法 / 后端服务 ｜ 2021.05 - 2022.06

**项目定位**：面向爱奇艺体育 APP 推荐页"猜你喜欢"、首页信息流和短视频 Feed 流场景，从 0 到 1 建设个性化推荐服务，提升内容分发效率、用户体验、用户渗透率和点击率等核心指标。

**技术栈**：Python、多路召回、DSSM、Wide&Deep、DeepFM、DIN、AB 实验。

- **推荐架构与召回策略设计**：与产品团队共同拆解推荐页和短视频 Feed 流业务需求，完成推荐服务技术方案设计、模块拆分和迭代规划，建设多路召回链路。
- **排序模型训练与迭代**：覆盖 DSSM、Wide&Deep、DeepFM、DIN 等排序模型实践，结合离线评估与 AB 实验闭环驱动模型迭代，持续优化 CTR、停留时长与用户渗透率等核心指标。
- **推荐后端服务全栈落地**：独立完成推荐后端服务代码开发、测试、调试部署和性能优化，支撑 APP 首页信息流、竖屏联播和短视频模块推荐场景上线。

**项目价值**：从 0 到 1 落地 Feed 流推荐服务，并扩展到爱奇艺体育 APP 竖屏联播、短视频模块等多个推荐场景。

---

## 教育背景

- **哈尔滨工程大学** ｜ 硕士 ｜ 软件工程 ｜ 2015.09 - 2018.03
- **哈尔滨工程大学** ｜ 学士 ｜ 信息与计算科学 ｜ 2011.09 - 2015.07

