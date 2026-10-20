<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" />
    <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" alt="Red Copilot — Security Engineering for the Agentic Era" width="100%" />
  </picture>
</p>

<p align="center">
  <strong>Security Engineering for the Agentic Era</strong><br/>
  <sub>面向智能体时代的安全工程</sub>
</p>

<h1 align="center">From Agent Actions to Verifiable Outcomes</h1>
<p align="center"><strong>从智能体行动，到可验证的结果</strong></p>

<p align="center">
  We build engineering systems that make security agents controllable, observable, and verifiable.<br/>
  <sub>我们构建可控、可观测、可验证的安全智能体工程系统。</sub>
</p>

<p align="center">
  <code>Plan</code> → <code>Execute</code> → <code>Observe</code> → <code>Verify</code><br/>
  <sub>规划 → 执行 → 观测 → 验证</sub>
</p>

<p align="center">
  <a href="https://github.com/orgs/red-copilot/repositories">Explore Repositories · 浏览仓库</a> ·
  <a href="https://github.com/red-copilot/.github/blob/main/CONTRIBUTING.md">Contribute · 参与贡献</a> ·
  <a href="https://github.com/red-copilot/.github/blob/main/SECURITY.md">Security Policy · 安全政策</a>
</p>

---

## What We Believe
<sub>我们的理念</sub>

### An agent's claim is not proof.
<sub>智能体的声明，不等于事实。</sub>

A model saying “done” does not prove that an objective has been achieved. A successful tool call does not guarantee a correct outcome.

Reliable automation needs more than model capability. It needs explicit authorization, bounded execution, observable behavior, recoverable workflows, and independent verification.

<sub>模型说“完成了”，不代表目标真的达成；工具调用成功，也不代表结果正确。可靠的自动化不仅需要模型能力，还需要明确的授权边界、受控执行、过程观测、失败恢复与独立验证。</sub>

## What We Build
<sub>我们构建什么</sub>

### Agent Execution & Evaluation
<sub>智能体执行与评测</sub>

We build runtimes that connect agents, tasks, tools, target environments, budgets, and verifiers through explicit contracts. Execution traces and results should be inspectable, reproducible, and comparable.

<sub>通过明确的接口约定连接智能体、任务、工具、目标环境、预算与验证器，让执行轨迹可检查、结果可复现、方案可比较。</sub>

### Controlled Security Automation
<sub>可控的安全自动化</sub>

We focus on authorization boundaries, environment isolation, credential handling, resource limits, and auditability for security workflows.

<sub>围绕安全工作流中的授权范围、环境隔离、凭据保护、资源限制与审计追踪开展工程实践。</sub>

### Attack Surface & Asset Reconnaissance
<sub>攻击面与资产侦察</sub>

We develop workflows for organizing assets, tracking observations, managing findings, and producing traceable results within authorized scopes.

<sub>在已授权范围内，探索资产组织、发现记录、风险管理与可追溯结果交付。</sub>

## Projects & Engineering
<sub>项目与工程实践</sub>

### [Red Harness · Python Runtime](https://github.com/red-copilot/red-copilot)
<sub>安全智能体执行与可复现评测运行时</sub>

A Python runtime for reproducible security-agent execution and evaluation. It connects benchmark tasks, Pi RPC sessions, isolated Kali containers, budgets, event-sourced world state, and independent verifiers. The current architecture entry point is [Architecture v2](https://github.com/red-copilot/red-copilot/blob/main/docs/agent-architecture-v2.md).

<sub>以 Python 实现安全智能体的可复现执行与评测，连接竞赛任务、Pi RPC 会话、隔离的 Kali 容器、预算、事件驱动的世界状态与独立验证器。当前架构入口为 [架构 v2](https://github.com/red-copilot/red-copilot/blob/main/docs/agent-architecture-v2.md)。</sub>

### [Red Harness Go SDK](https://github.com/red-copilot/harness)
<sub>Go 原生执行边界与 SDK</sub>

A separate Go implementation exposing Library, CLI, and HTTP integration surfaces. It focuses on container isolation, execution budgets, SQLite audit records, and verifier-controlled outcomes. Its credential boundary differs from the Python runtime; consult the repository documentation for exact behavior.

<sub>独立的 Go 实现，提供 Library、CLI 与 HTTP 接入方式，重点关注容器隔离、执行预算、SQLite 审计记录与验证器控制的结果。它与 Python Runtime 的凭据边界不同，具体行为以仓库文档为准。</sub>

### [ARL 3.0 · Asset Reconnaissance Lighthouse](https://github.com/red-copilot/red-x)
<sub>授权资产侦察与外部攻击面管理</sub>

A Go-based EASM and asset-reconnaissance platform that organizes organizations, domains, assets, findings, and tasks into traceable workflows. It includes an embedded React console, REST/SSE APIs, PostgreSQL-backed data, and Redis Streams task processing.

<sub>基于 Go 的 EASM 与资产侦察平台，将组织、域名、资产、风险和任务组织为可追溯工作流，并提供嵌入式 React 控制台、REST/SSE API、PostgreSQL 数据存储与 Redis Streams 任务处理。</sub>

### [Organization profile & shared standards](https://github.com/red-copilot/.github)
<sub>组织主页与共享规范</sub>

Brand assets, community health files, contribution guidance, and security policy for the organization.

<sub>组织品牌素材、社区规范、贡献指南与安全政策。</sub>

## How We Approach Engineering
<sub>我们的工程原则</sub>

| Principle | 实践原则 |
|---|---|
| **Authorization first** | **授权优先：** 明确目标范围与权限边界后再执行。 |
| **Evidence over claims** | **证据优先：** 依据可检查的证据判断结果，而不是依赖模型自述。 |
| **Isolation by design** | **默认隔离：** 限制环境、凭据与资源访问，降低越界风险。 |
| **Bounded execution** | **有界执行：** 对权限、时长、调用量与资源消耗设定限制。 |
| **Reproducibility** | **可复现：** 保留关键配置、执行轨迹与结果，支持审计和比较。 |
| **Clear boundaries** | **职责清晰：** 区分任务、环境、智能体、模型、工具与验证器。 |

## Join the Work
<sub>参与建设</sub>

Explore the repositories to see what is implemented today. Contributions are welcome in the form of reproducible bug reports, tests, documentation, architecture discussions, and code.

<sub>欢迎浏览仓库了解当前实现，也欢迎通过可复现的问题报告、测试、文档、架构讨论与代码参与建设。</sub>

<p align="center">
  <strong>Build agents that can act. Engineer systems that can prove the outcome.</strong>
  <br/>
  <sub>构建能够行动的智能体，打造能够验证结果的工程系统。</sub>
</p>

<p align="center"><sub>For authorized security testing, competitions, and research only. · 仅用于已获授权的安全测试、竞赛与研究。</sub></p>
