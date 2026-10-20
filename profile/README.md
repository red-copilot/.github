<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-animated.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" />
    <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" alt="Red Copilot — Security Engineering for the Agentic Era" width="100%" />
  </picture>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=1100&color=F05260&center=true&vCenter=true&width=760&lines=Security+Engineering+for+the+Agentic+Era;From+Agent+Actions+to+Verifiable+Outcomes;面向智能体时代的安全工程" alt="Security Engineering for the Agentic Era" />
</p>

<p align="center">
  <a href="https://github.com/orgs/red-copilot/repositories">Explore Projects ↗</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/BRAND.md">Brand Standards ↗</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/CONTRIBUTING.md">Contribute ↗</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/SECURITY.md">Security Policy ↗</a>
</p>

<p align="center">
  We build security-agent systems that are controllable, observable, and verifiable.<br/>
  <sub>我们构建可控、可观测、可验证的安全智能体工程系统。</sub>
</p>

<p align="center">
  <code>PLAN</code> → <code>EXECUTE</code> → <code>OBSERVE</code> → <code>VERIFY</code><br/>
  <sub>规划 → 执行 → 观测 → 验证</sub>
</p>

---

## 01 / Our Thesis
<sub>我们的核心观点</sub>

### An agent's claim is not proof.
<sub>智能体的声明，不等于事实。</sub>

A model saying “done” does not prove that the objective was achieved. Reliable automation needs explicit authorization, bounded execution, observable traces, recoverable workflows, and independent verification.

<sub>模型说“完成了”，不代表目标真的达成。可靠的自动化需要明确授权、有界执行、过程观测、失败恢复与独立验证。</sub>

## 02 / What We Build
<sub>核心项目</sub>

<table>
  <tr>
    <td width="84" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-red-harness.svg" width="68" alt="Red Harness Python Runtime" />
    </td>
    <td valign="top">
      <strong><a href="https://github.com/red-copilot/red-copilot">Red Harness · Python Runtime</a></strong><br/>
      <sub>安全智能体执行与可复现评测运行时</sub><br/><br/>
      Connects benchmark tasks, Pi RPC sessions, isolated Kali containers, budgets, event-sourced world state, and independent verifiers.<br/>
      <sub>连接竞赛任务、Pi RPC 会话、隔离的 Kali 容器、预算、事件驱动的世界状态与独立验证器。</sub><br/><br/>
      <a href="https://github.com/red-copilot/red-copilot/blob/main/docs/agent-architecture-v2.md">Architecture v2 ↗</a>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-harness-sdk.svg" width="68" alt="Red Harness Go SDK" />
    </td>
    <td valign="top">
      <strong><a href="https://github.com/red-copilot/harness">Red Harness · Go SDK</a></strong><br/>
      <sub>Go 原生执行边界与 SDK</sub><br/><br/>
      A separate Go implementation with Library, CLI, and HTTP interfaces, focused on container isolation, execution budgets, SQLite auditing, and verifier-controlled outcomes.<br/>
      <sub>独立的 Go 实现，提供 Library、CLI 与 HTTP 接入，聚焦容器隔离、执行预算、SQLite 审计与验证器控制的结果。</sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-arl.svg" width="68" alt="ARL 3.0" />
    </td>
    <td valign="top">
      <strong><a href="https://github.com/red-copilot/red-x">ARL 3.0 · Asset Reconnaissance Lighthouse</a></strong><br/>
      <sub>授权资产侦察与外部攻击面管理</sub><br/><br/>
      A Go-based EASM platform for organizing organizations, domains, assets, findings, and tasks into traceable workflows, with a React console and REST/SSE APIs.<br/>
      <sub>基于 Go 的 EASM 平台，将组织、域名、资产、发现与任务组织为可追溯工作流，并提供 React 控制台与 REST/SSE API。</sub>
    </td>
  </tr>
</table>

## 03 / Engineering Principles
<sub>工程原则</sub>

**Authorization first. Evidence over claims. Isolation by design. Bounded execution. Reproducibility.**

<sub>授权优先。证据优先。默认隔离。有界执行。可复现。</sub>

We favor clear boundaries between tasks, agents, tools, target environments, and verifiers. Results should be inspectable, auditable, and repeatable—not accepted solely because a model says it succeeded.

<sub>我们强调任务、智能体、工具、目标环境与验证器之间的清晰边界。结果应当可检查、可审计、可复现，而不是仅凭模型自述认定成功。</sub>

## 04 / Build With Us
<sub>参与建设</sub>

We welcome reproducible bug reports, tests, documentation, architecture discussions, and code contributions. Explore a project, inspect what is implemented today, and help make the next result easier to verify.

<sub>欢迎通过可复现的问题报告、测试、文档、架构讨论与代码参与建设。欢迎了解项目当前实现，并一起让结果更容易被验证。</sub>

<p align="center">
  <a href="https://github.com/orgs/red-copilot/repositories">Browse repositories ↗</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/CONTRIBUTING.md">Contribution guide ↗</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/SECURITY.md">Security policy ↗</a>
</p>

<p align="center">
  <strong>Build agents that can act. Engineer systems that can prove the outcome.</strong><br/>
  <sub>构建能够行动的智能体，打造能够验证结果的工程系统。</sub>
</p>

<p align="center"><sub>For authorized security testing, competitions, and research only. · 仅用于已获授权的安全测试、竞赛与研究。</sub></p>
