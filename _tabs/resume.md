---
icon: fas fa-file-alt
order: 4
---

<style>
  /* ── 小节标题 ── */
  .resume-section h2 {
    border-bottom: 2px solid #448aff;
    padding-bottom: 0.3rem;
    margin-top: 2.2rem;
    margin-bottom: 1rem;
  }
  /* ── 联系行 ── */
  .contact-line { color: #888; font-size: 0.95rem; }
  /* ── 奖项列表 ── */
  .award-list { list-style: none; padding-left: 0; }
  .award-list li { margin-bottom: 0.3rem; }
  .award-list li::before { content: "🏅 "; }
  /* ── 项目卡片 ── */
  .project-card {
    border-left: 3px solid #448aff;
    padding: 1rem 1.25rem;
    margin-bottom: 1.25rem;
    border-radius: 0 0.5rem 0.5rem 0;
    background: rgba(68,138,255,0.04);
  }
  .project-card h4 { margin-top: 0; color: inherit; }
  .project-card ul { margin-bottom: 0; }
  /* ── 技能标签 ── */
  .skill-group { margin-bottom: 0.7rem; line-height: 2; }
  .skill-label { font-weight: 600; display: inline-block; min-width: 7rem; }
  .skill-tag {
    display: inline-block;
    background: #e3f2fd;
    color: #1565c0;
    padding: 0.15rem 0.55rem;
    border-radius: 0.3rem;
    margin: 0 0.25rem 0.15rem 0;
    font-size: 0.85rem;
    font-weight: 500;
  }
  /* ── 暗色模式 ── */
  @media (prefers-color-scheme: dark) {
    .contact-line { color: #999; }
    .project-card { background: rgba(68,138,255,0.06); }
    .skill-tag { background: #1e3a5f; color: #90caf9; }
  }
  html[data-mode="dark"] .contact-line { color: #999; }
  html[data-mode="dark"] .project-card { background: rgba(68,138,255,0.06); }
  html[data-mode="dark"] .skill-tag { background: #1e3a5f; color: #90caf9; }
</style>

<div class="resume-section" markdown="1">

# 孙訢源

<p class="contact-line">软件工程 · 南京大学 · 2023 - 2027（预计） · <a href="mailto:231250074@smail.nju.edu.cn">Email</a> · <a href="https://github.com/sunxi2077">GitHub</a></p>

</div>

<div class="resume-section" markdown="1">

## 教育经历

**南京大学 · 软件工程 · 本科**&ensp;·&ensp;GPA **4.48** / 5.0

<ul class="award-list">
  <li>软件学院高额奖学金（腾讯奖学金）、人民奖学金</li>
  <li>全国大学生物联网设计竞赛 · 全国一等奖（无人机方向）</li>
  <li>南京大学优秀共青团员、国家级大创项目主持人</li>
</ul>

</div>

<div class="resume-section" markdown="1">

## 项目经历

<div class="project-card" markdown="1">

#### Multi-Agent Harness 工程原型

基于 Python 与 Anthropic API 的 Multi-Agent Harness 框架，围绕工具调用、任务编排、上下文压缩与多智能体协作，构建面向复杂软件任务的智能体运行平台。

- 设计轻量级 **Agent Loop** 工具调用框架，封装文件读写、Shell 执行、任务管理等原子能力
- 实现**任务持久化与状态编排**，基于 JSON 文件管理任务生命周期，支持跨会话恢复
- 构建 **Multi-Agent 协作**机制，通过 JSONL 邮箱实现主 Agent 与子 Agent 的异步通信与任务分发
- 基于 Git Worktree 实现**任务级隔离执行**，绑定独立工作目录，保障多任务并发安全

</div>

<div class="project-card" markdown="1">

#### FreeRead — RAG 知识库问答系统

基于 Spring Boot 的面向私有知识库场景的智能问答平台，支持多格式文档上传与自然语言交互检索。

- 构建 **RAG 主链路**：Kafka 解耦上传与处理，Redis Bitmap 追踪分片状态
- 实现**混合检索**：Elasticsearch + KNN 向量召回 + BM25 重排，异常时自动降级
- 设计**语义优先分层切块**策略：段落 → 句子 → HanLP 分词，兼顾长度与语义完整
- 结合 Spring Security + JWT 构建多租户权限体系，ES Bool Filter 层安全阻断越权

</div>

</div>

<div class="resume-section" markdown="1">

## 专业技能

<div class="skill-group">
  <span class="skill-label">AI / Agent</span>
  <span class="skill-tag">Agent Loop</span><span class="skill-tag">Tool Calling</span><span class="skill-tag">上下文压缩</span><span class="skill-tag">多 Agent 协作</span><span class="skill-tag">任务持久化</span>
</div>
<div class="skill-group">
  <span class="skill-label">后端开发</span>
  <span class="skill-tag">Java</span><span class="skill-tag">Spring Boot</span><span class="skill-tag">Spring Security</span><span class="skill-tag">MyBatis-Plus</span><span class="skill-tag">FastAPI</span>
</div>
<div class="skill-group">
  <span class="skill-label">检索 & 数据</span>
  <span class="skill-tag">Elasticsearch</span><span class="skill-tag">BM25</span><span class="skill-tag">KNN</span><span class="skill-tag">MySQL</span><span class="skill-tag">Redis</span><span class="skill-tag">MinIO</span><span class="skill-tag">Kafka</span>
</div>
<div class="skill-group">
  <span class="skill-label">工程实践</span>
  <span class="skill-tag">Docker</span><span class="skill-tag">Linux</span><span class="skill-tag">Git</span><span class="skill-tag">Maven</span><span class="skill-tag">链路追踪</span><span class="skill-tag">回归测试</span>
</div>

</div>

<div class="resume-section" markdown="1">

## 更多

> 完整简历可[邮件联系](mailto:231250074@smail.nju.edu.cn)。

</div>
