<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" />
    <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" alt="Red Copilot — From agent actions to verifiable outcomes. 从智能体行动到可验证的结果。" width="100%" />
  </picture>
</p>

<p align="center">
  <a href="https://github.com/orgs/red-copilot/repositories">Projects · 核心项目 ↗</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/BRAND.md">Brand · 品牌规范 ↗</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/CONTRIBUTING.md">Contribute · 参与共建 ↗</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/SECURITY.md">Security · 安全政策 ↗</a>
</p>

<p align="center">
  We engineer security-agent systems that are controllable, observable, and verifiable.<br/>
  <sub>我们构建可控、可观测、可验证的安全智能体工程系统。</sub>
</p>

---

## Three systems. One control loop.

<sub>三套系统，一条控制回路。</sub>

Different scopes, one contract: the agent owns reasoning, the runtime owns boundaries, and the verifier owns truth.

<sub>范围不同，契约一致：智能体负责推理，运行时负责边界，验证器负责事实。</sub>

### <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-red-harness.svg" width="40" align="center" alt="" /> Red Harness · Python Runtime

**EVALUATE / 可复现执行与评测**

A reproducible runtime for security-agent tasks and benchmarks, connecting Pi RPC sessions, isolated Kali containers, execution budgets, event-sourced world state, and independent verification.

<sub>面向安全智能体任务与基准测试的可复现运行时，连接 Pi RPC 会话、隔离的 Kali 容器、执行预算、事件驱动的世界状态与独立验证。</sub>

[Architecture v2 ↗](https://github.com/red-copilot/red-copilot/blob/main/docs/agent-architecture-v2.md) · [Repository ↗](https://github.com/red-copilot/red-copilot)

### <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-harness-sdk.svg" width="40" align="center" alt="" /> Harness SDK · Go

**EXECUTE / Go 原生执行边界**

An independent Go-native runtime exposed as a library, CLI, and local HTTP service. It governs container isolation, execution budgets, SQLite audit records, recovery, and verifier-controlled outcomes.

<sub>独立的 Go 原生执行边界，提供库、CLI 与本地 HTTP 服务，覆盖容器隔离、执行预算、SQLite 审计记录、恢复与由验证器裁定的结果。</sub>

[Repository ↗](https://github.com/red-copilot/harness)

### <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-arl.svg" width="40" align="center" alt="" /> ARL 3.0 · EASM

**DISCOVER / 授权优先的外部攻击面管理**

An authorization-first platform that organizes domains, assets, findings, and tasks into traceable workflows, with an embedded React console and REST/SSE APIs.

<sub>授权优先的外部攻击面管理平台，将域名、资产、风险与任务组织为可追溯工作流，并提供嵌入式 React 控制台与 REST/SSE API。</sub>

[Repository ↗](https://github.com/red-copilot/red-x)

---

## Authorization is the starting condition. Evidence is the ending condition.

<sub>以授权为起点，以证据为终点。</sub>

<p align="center">
  <code>AUTHORIZE</code> 授权 &nbsp;→&nbsp;
  <code>CONTAIN</code> 隔离 &nbsp;→&nbsp;
  <code>OBSERVE</code> 观测 &nbsp;→&nbsp;
  <code>VERIFY</code> 验证
</p>

An agent's claim is not proof. Reliable automation requires explicit authorization, bounded execution, observable traces, recoverable workflows, and independent verification.

<sub>智能体的声明不等于事实。可靠的自动化需要明确授权、有界执行、可观测轨迹、失败恢复与独立验证。</sub>

**Authorization first. Evidence over claims. Isolation by design. Bounded execution. Reproducibility.**

<sub>授权优先 · 证据优先 · 默认隔离 · 有界执行 · 可复现</sub>

---

## Build with us

<sub>参与共建</sub>

We welcome reproducible bug reports, tests, documentation, architecture discussions, and code. Read the contribution guide before starting substantial work, and use the security policy for vulnerability reports.

<sub>欢迎通过可复现的问题报告、测试、文档、架构讨论与代码参与建设。开始较大改动前请阅读贡献指南；漏洞报告请遵循安全政策。</sub>

[Browse repositories ↗](https://github.com/orgs/red-copilot/repositories) · [Contribution guide ↗](https://github.com/red-copilot/.github/blob/main/CONTRIBUTING.md) · [Security policy ↗](https://github.com/red-copilot/.github/blob/main/SECURITY.md)

<p align="center">
  <strong>Build agents that can act. Engineer systems that can prove the outcome.</strong><br/>
  <sub>构建能够行动的智能体，打造能够验证结果的工程系统。</sub>
</p>

<p align="center"><sub>For authorized security testing, competitions, and research only. · 仅用于已获授权的安全测试、竞赛与研究。</sub></p>
