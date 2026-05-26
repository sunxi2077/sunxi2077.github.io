---
icon: fas fa-file-alt
order: 4
---

# 孙訢源

**软件工程专业本科生** · 南京大学 · 2023.09 - 2027.06（预计）

📧 [231250074@smail.nju.edu.cn](mailto:231250074@smail.nju.edu.cn) · 💻 [GitHub](https://github.com/sunxi2077)

---

## 教育经历

**南京大学 · 软件工程 · 本科**  
GPA 4.48 / 5.0

**曾获奖项：**
- 软件学院高额奖学金（腾讯奖学金）、人民奖学金
- 全国大学生物联网设计竞赛全国一等奖（无人机方向）
- 南京大学优秀共青团员、国家级大创项目主持人

---

## 项目经历

### Multi-Agent Harness 工程原型

基于 Python 与 Anthropic API 实现的 Multi-Agent Harness 工程框架，面向复杂软件任务场景，支持工具调用、任务编排、上下文压缩与多智能体协作。

- 设计轻量级 **Agent Loop** 工具调用框架，封装文件读写、Shell 执行、任务管理等原子能力
- 实现**任务持久化与状态编排**，基于 JSON 文件管理任务生命周期，支持跨会话恢复
- 构建 **Multi-Agent 协作**机制，通过 JSONL 邮箱实现主 Agent 与子 Agent 的异步通信与任务分发
- 基于 Git Worktree 实现**任务级隔离执行**，绑定独立工作目录，保障多任务并发安全

### FreeRead — RAG 知识库问答系统

基于 Spring Boot 的面向私有知识库场景的智能问答平台，支持多格式文档上传与自然语言交互检索。

- 构建 **RAG 主链路**：Kafka 解耦上传与处理，Redis Bitmap 追踪分片状态，支持 Word/PDF/TXT
- 实现**混合检索**：Elasticsearch + KNN 向量召回 + BM25 重排，异常时自动降级为纯文本检索
- 设计**语义优先分层切块**策略：段落 → 句子 → HanLP 分词，兼顾 chunk 长度与语义完整性
- 结合 Spring Security + JWT 构建多租户权限体系，通过 ES Bool Filter 在检索引擎层安全阻断越权

---

## 专业技能

| 方向 | 技能 |
|------|------|
| **AI / Agent** | Agent Loop, Tool Calling, 上下文压缩, 多 Agent 协作, 任务持久化 |
| **后端开发** | Java, Spring Boot, Spring Security, MyBatis-Plus, FastAPI |
| **检索 & 数据** | Elasticsearch, BM25, KNN 向量检索, MySQL, Redis, MinIO, Kafka |
| **工程实践** | Docker, Linux, Git, Maven, 链路追踪, 回归测试 |

---

> 完整简历可[邮件联系](mailto:231250074@smail.nju.edu.cn)。
