<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" />
    <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" alt="Red Copilot — AI-Native Offensive Security Engineering" width="100%" />
  </picture>
</p>

<p align="center">
  <strong>AI-NATIVE SECURITY ENGINEERING</strong><br/>
  <sub>面向智能体时代的安全工程</sub>
</p>

<h1 align="center">Autonomy is not enough.<br/>Make it measurable.</h1>
<p align="center"><sub>仅有自主能力还不够，更要让能力可衡量、可验证。</sub></p>

<p align="center">
  We build the infrastructure for security agents to plan, act, learn from feedback, and prove outcomes.
  <br/>
  <sub>我们构建安全智能体的工程基础设施，让它们能够规划、执行、接收反馈，并以证据证明结果。</sub>
</p>

<p align="center">
  <code>PLAN</code> → <code>EXECUTE</code> → <code>OBSERVE</code> → <code>VERIFY</code>
  <br/>
  <sub>规划 → 执行 → 观测 → 验证</sub>
</p>

<p align="center">
  <a href="https://github.com/orgs/red-copilot/repositories">Explore repositories</a> ·
  <a href="https://github.com/red-copilot/.github/blob/main/CONTRIBUTING.md">Contribute</a> ·
  <a href="https://github.com/red-copilot/.github/blob/main/SECURITY.md">Security</a>
  <br/>
  <sub>浏览项目 · 参与贡献 · 安全政策</sub>
</p>

---

## What we believe
<sub>我们的理念</sub>

### An agent's claim is not evidence.
<sub>智能体的自我声明，不等于可信证据。</sub>

Reliable security automation takes more than a capable model. It needs explicit scope, controlled execution, useful feedback, recoverable workflows, and independent verification.

<sub>可靠的安全自动化不只依赖强大的模型，还需要明确的任务范围、受控执行、有效反馈、可恢复的工作流，以及独立验证机制。</sub>

## What we build
<sub>我们构建什么</sub>

<table>
  <tr>
    <td width="33%" valign="top">
      <p><strong>01 / AGENT RUNTIME</strong></p>
      <h3>Coordinate complex work</h3>
      <p>Planning, tool orchestration, state management, feedback loops, and failure recovery.</p>
      <p><sub>规划、工具编排、状态管理、反馈闭环与故障恢复。</sub></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>02 / EXECUTION CONTROL</strong></p>
      <h3>Keep actions bounded</h3>
      <p>Authorization scope, isolated environments, least privilege, resource budgets, and audit trails.</p>
      <p><sub>授权范围、环境隔离、最小权限、资源预算与审计轨迹。</sub></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>03 / VERIFICATION</strong></p>
      <h3>Prove what happened</h3>
      <p>Task contracts, independent checks, reproducible experiments, and evidence-backed results.</p>
      <p><sub>任务契约、独立检查、可复现实验与证据驱动的结果判定。</sub></p>
    </td>
  </tr>
</table>

## How the system works
<sub>系统如何工作</sub>

```mermaid
flowchart LR
    A["Agent<br/>智能体"] --> B["Harness<br/>运行控制"]
    B --> C["Tools & Environment<br/>工具与环境"]
    C --> D["Observations<br/>执行观测"]
    D --> A
    C --> E["Verifier<br/>独立验证"]
    E --> F["Evidence<br/>结果证据"]
    F -. feedback .-> A
    classDef core fill:#451010,stroke:#ef4444,color:#fff,stroke-width:2px;
    classDef node fill:#18181b,stroke:#71717a,color:#fafafa;
    class B,E core;
    class A,C,D,F node;
```

<p align="center">
  The agent proposes. The environment responds. The verifier decides.
  <br/>
  <sub>智能体提出行动，环境反馈结果，验证器依据证据作出判定。</sub>
</p>

## Project portfolio
<sub>项目版图</sub>

<table>
  <tr>
    <td width="33%" valign="top">
      <p><strong>01 — EVALUATION</strong></p>
      <h3><a href="https://github.com/red-copilot/red-harness">Red Harness</a></h3>
      <p>A controlled, reproducible environment for testing security-agent capabilities.</p>
      <p><sub>用于测试安全智能体能力的受控、可复现运行环境。</sub></p>
      <p><code>Agent Evaluation</code><br/><code>Python</code> · <code>Docker</code></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>02 — EXECUTION</strong></p>
      <h3>Red Harness Go SDK</h3>
      <p>Go-native building blocks for controlled execution and integration.</p>
      <p><sub>面向受控执行与系统集成的 Go 原生基础组件。</sub></p>
      <p><code>Go</code> · <code>SDK</code> · <code>Runtime</code></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>03 — RECONNAISSANCE</strong></p>
      <h3>Attack Surface Intelligence</h3>
      <p>Asset discovery and security workflows designed around traceability and authorization.</p>
      <p><sub>以可追踪性与授权为核心的资产发现和安全工作流。</sub></p>
      <p><code>Attack Surface</code> · <code>Automation</code></p>
    </td>
  </tr>
</table>

## Engineering principles
<sub>工程原则</sub>

| Principle | 中文说明 |
|---|---|
| **Authorization first** | 先确认授权与测试边界，再执行安全任务。 |
| **Evidence over claims** | 结论由可检查的证据支持，而不是模型自述。 |
| **Isolation by default** | 默认隔离执行环境、凭据与资源访问。 |
| **Bounded execution** | 对权限、时间、调用次数与资源消耗设置边界。 |
| **Reproducibility** | 让任务、环境、轨迹和结果可审计、可回放、可比较。 |

---

<p align="center">
  <strong>Build agents that can act. Engineer systems that can prove.</strong>
  <br/>
  <sub>构建能够行动的智能体，打造能够验证结果的工程系统。</sub>
</p>

<p align="center">
  <a href="https://github.com/orgs/red-copilot/repositories">All repositories ↗</a>
  <br/>
  <sub>查看全部仓库</sub>
</p>

<p align="center"><sub>For authorized security testing and research only.<br/>仅用于获得授权的安全测试与研究。</sub></p>
