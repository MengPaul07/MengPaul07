<div align="center">

# Hey, I'm Paul Meng 👋

**CS Undergrad @ 北京交通大学 计算机科学与技术(2025–) · Beijing, CN**

[![GitHub](https://img.shields.io/badge/GitHub-MengPaul07-24292e?style=flat&logo=github)](https://github.com/MengPaul07)

</div>

---

### 🧠 What I'm Into

<table>
<tr>
<td width="50%">

**Agent Engineering** — I care about loop internals, not framework wrappers. Function-calling engines, multi-agent orchestration, tool management. Built from scratch.

**Harness Engineering** — SSE streaming, retry strategies, error taxonomies, graceful degradation. The scaffolding matters as much as the model.

</td>
<td width="50%">

**Agent 工程** — 关心循环引擎的里层，不是框架的壳。工具调用、多 Agent 编排、调度设计，都从零写过。

**工程底座** — SSE 流式推送、分级重试、错误码分类、降级兜底。脚手架和模型本身一样值钱。

</td>
</tr>
</table>

---

### 🔧 Projects

#### [Resume Studio](https://github.com/MengPaul07/resume-studio) — AI-Native Resume Workspace

<table>
<tr>
<td width="50%">

- Custom ReAct Agent Loop — **SSE streaming**, real-time tool-call tracing, **HITL pause/resume**
- FAISS + FastEmbed local RAG, **10K-scale benchmark** (MRR 0.80, Hit Rate@5 0.88)
- **4-category fault taxonomy** — timeout→retry, rate-limit→backoff, overflow→truncate, auth→fail fast
- FastAPI + React 19 + SQLite, **191 unit tests + 37 LLM regression tests**

</td>
<td width="50%">

- 自研 ReAct Agent 循环引擎 — SSE 流式推送，工具调用链路可观测，人机协同可暂停
- FAISS 本地向量检索，万级语料定量评估（MRR 0.80, Hit Rate@5 0.88）
- **四类异常分级重试** — 超时重试、限流退避、上下文截断、鉴权直接报错
- 全栈自建，**191 单元测试 + 37 LLM 回归测试**

</td>
</tr>
</table>

---

#### [Paulo CLI](https://github.com/MengPaul07/paulo-cli) — Multi-Agent Coding CLI

<table>
<tr>
<td width="50%">

- **3-tier agent orchestration** — Master decomposes, Sub agents execute, Agent Teams async long-run
- **Inbox-driven collaboration** — agents scan a shared task board, claim work autonomously
- **Defense in depth** — path sandbox, command blacklist, HITL approval gates, tiered tool permissions
- **Persistent memory** — 4-type auto-extraction, dedup, dynamic System Prompt injection
- **Zero agent framework** — pure Python + Anthropic SDK, 37 tests

</td>
<td width="50%">

- **三级 Agent 编排** — Master 拆任务，Sub 同步执行，Agent Team 异步长周期协作
- **收件箱式协作** — 空闲 Agent 自动扫描公共任务板，认领未分配工作
- **纵深防御** — 路径沙箱、命令黑名单、HITL 审批门禁、三级权限预设
- **分类持久记忆** — 四类自动提取与去重，每次调用前动态注入 System Prompt
- **零框架依赖** — 纯 Python + Anthropic SDK，37 个测试

</td>
</tr>
</table>

---

### 🛠 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![FAISS](https://img.shields.io/badge/-FAISS-0866FF?style=flat)
![LiteLLM](https://img.shields.io/badge/-LiteLLM-4B32C3?style=flat)
![Anthropic](https://img.shields.io/badge/-Anthropic%20SDK-191919?style=flat)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)

</div>

---

