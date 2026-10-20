<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" />
    <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" alt="Red Copilot — AI-Native Offensive Security Engineering" width="100%" />
  </picture>
</p>

<p align="center">
  <sub>INDEPENDENT SECURITY ENGINEERING · AGENT SYSTEMS · REPRODUCIBLE EVALUATION</sub>
</p>

<h1 align="center">Autonomy needs control.<br/>Results need evidence.</h1>
<p align="center"><sub>自主能力需要工程控制，任务结果必须有证据支撑。</sub></p>

<p align="center">
  We engineer the systems that make security agents measurable, bounded, and reliable.
  <br/>
  <sub>我们构建让安全智能体可衡量、可约束、可信赖的工程系统。</sub>
</p>

<p align="center">
  <code>PLAN</code> &nbsp;→&nbsp; <code>EXECUTE</code> &nbsp;→&nbsp; <code>OBSERVE</code> &nbsp;→&nbsp; <code>VERIFY</code>
  <br/>
  <sub>规划 → 执行 → 观察 → 验证</sub>
</p>

---

## The idea
<sub>核心理念</sub>

**A model saying “done” is not a test passing.**

The hard part of an autonomous security agent is not just choosing the next tool. It is controlling what the agent can do, giving it useful feedback, recovering from failure, and independently proving what happened.

<sub>**模型说“完成了”，不等于测试真正通过。** 自主安全智能体的难点不只是选择工具，而是约束执行权限、提供有效反馈、从失败中恢复，并独立验证实际发生的结果。</sub>

## What we engineer
<sub>工程方向</sub>

<table>
  <tr>
    <td width="33%" valign="top">
      <p><strong>01 / AGENT SYSTEMS</strong></p>
      <h3>Make agents adaptive</h3>
      <p>Multi-step planning, tool use, state tracking, feedback, and recovery.</p>
      <p><sub>让智能体具备多步骤规划、工具调用、状态跟踪、反馈处理与故障恢复能力。</sub></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>02 / EXECUTION CONTROL</strong></p>
      <h3>Make actions bounded</h3>
      <p>Explicit scope, isolated environments, least privilege, budgets, and audit trails.</p>
      <p><sub>通过明确授权范围、环境隔离、最小权限、预算限制与审计轨迹约束执行。</sub></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>03 / EVALUATION</strong></p>
      <h3>Make outcomes verifiable</h3>
      <p>Task contracts, independent verification, reproducible runs, and comparable results.</p>
      <p><sub>以任务契约、独立验证、可复现运行和可比较结果衡量系统能力。</sub></p>
    </td>
  </tr>
</table>

## System architecture
<sub>系统架构</sub>

```mermaid
flowchart TD
    A["Agent / Planner<br/>智能体与规划器"] --> B["Harness Runtime<br/>运行时与执行控制"]
    B --> C["Isolated Environment<br/>隔离执行环境"]
    C --> D["Observations & Traces<br/>观测结果与执行轨迹"]
    D --> A
    C --> E["Independent Verifier<br/>独立验证器"]
    E --> F["Evidence-based Verdict<br/>基于证据的结果判定"]
    F -. evaluation feedback .-> A
    classDef agent fill:#18181b,stroke:#71717a,color:#fafafa;
    classDef runtime fill:#450a0a,stroke:#ef4444,color:#fff1f2,stroke-width:2px;
    classDef env fill:#27272a,stroke:#a1a1aa,color:#fafafa;
    classDef verify fill:#3f1010,stroke:#f87171,color:#fff;
    class A agent;
    class B runtime;
    class C,D env;
    class E,F verify;
```

<p align="center"><sub>The agent proposes actions. The environment produces observations. The verifier determines success.<br/>智能体提出行动，环境产生观测，验证器判定是否成功。</sub></p>

## Project portfolio
<sub>项目版图</sub>

<table>
  <tr>
    <td width="33%" valign="top">
      <p><strong>01 — EVALUATE</strong></p>
      <h3>Red Harness</h3>
      <p>A reproducible runtime for evaluating security agents through task contracts, bounded execution, telemetry, and authoritative verification.</p>
      <p><sub>面向安全智能体的可复现评测运行时，整合任务契约、受控执行、运行遥测与权威验证。</sub></p>
      <p><code>Agent Evaluation</code> <code>Python</code> <code>Docker</code></p>
      <p><sub>Repository: private development</sub></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>02 — EXECUTE</strong></p>
      <h3>Harness Go SDK</h3>
      <p>A Go-native execution boundary for controlled tool access, isolated workloads, audit records, and verification.</p>
      <p><sub>原生 Go 执行边界，为受控工具访问、隔离任务、审计记录和结果验证提供基础能力。</sub></p>
      <p><code>Go</code> <code>Docker</code> <code>SQLite</code></p>
      <p><sub>Repository: private development</sub></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>03 — DISCOVER</strong></p>
      <h3>ARL / red-x</h3>
      <p>An authorization-first attack-surface and asset reconnaissance platform built around traceable assets, risks, tasks, and reports.</p>
      <p><sub>以授权为先的攻击面管理与资产侦察平台，围绕可追踪的资产、风险、任务和报告组织工作流。</sub></p>
      <p><code>Attack Surface</code> <code>Go</code> <code>React</code></p>
      <p><sub>Repository: private development</sub></p>
    </td>
  </tr>
</table>

## Engineering principles
<sub>工程原则</sub>

| Principle | 中文说明 |
|---|---|
| **Authorization first** | 授权是开始测试的前置条件，不是事后补充的免责声明。 |
| **Evidence over claims** | 智能体自述不是成功证据；结论必须来自独立验证。 |
| **Isolation by default** | 默认隔离环境、网络、凭据与文件系统；高风险能力必须显式启用。 |
| **Bounded execution** | 对范围、时间、调用次数和资源消耗设置明确边界。 |
| **Reproducibility** | 让任务、环境、执行轨迹和结果可审计、可回放、可比较。 |

## Explore
<sub>了解与参与</sub>

<p align="center">
  <a href="https://github.com/orgs/red-copilot/repositories"><strong>Browse repositories ↗</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/CONTRIBUTING.md">Contributing</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/SECURITY.md">Security policy</a>
  <br/>
  <sub>浏览仓库 · 参与贡献 · 阅读安全政策</sub>
</p>

<p align="center">
  <strong>Build autonomous systems. Prove real outcomes.</strong>
  <br/>
  <sub>构建自主系统，以真实结果验证能力。</sub>
</p>

<p align="center"><sub>Security testing must be limited to systems you own or are explicitly authorized to assess.<br/>所有安全测试仅限于自有系统或已获得明确授权的目标。</sub></p>
