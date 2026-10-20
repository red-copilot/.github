<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" />
    <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" alt="Red Copilot — AI × Offensive Security" width="100%" />
  </picture>
</p>

<h2 align="center">AI-Native Offensive Security Engineering<br/><sub>面向 AI 的进攻性安全工程</sub></h2>

<p align="center">
  <strong>Build autonomous systems. Prove real outcomes.</strong><br/><sub>构建自主系统，以真实结果验证能力。</sub><br/><sub>构建自主系统，以真实结果验证能力。</sub>
</p>

<p align="center">
  <kbd>PLAN</kbd>&nbsp;&nbsp;→&nbsp;&nbsp;
  <kbd>EXECUTE</kbd>&nbsp;&nbsp;→&nbsp;&nbsp;
  <kbd>OBSERVE</kbd>&nbsp;&nbsp;→&nbsp;&nbsp;
  <kbd>VERIFY</kbd>
</p>

---

## What we build

<small>我们构建什么</small>

Red Copilot engineers reliable AI systems for offensive security. We build the infrastructure around the model: execution boundaries, tool feedback, state tracking, budget control, observability, and independent verification.

<small>Red Copilot 致力于构建可靠的 AI 进攻性安全系统。我们关注模型之外的工程基础设施：执行边界、工具反馈、状态跟踪、预算控制、可观测性与独立验证。</small>

**A convincing agent response is not proof of success.** Systems should be judged by reproducible outcomes and evidence from the environment—not by the model’s claims alone.

<small>智能体给出令人信服的回答，不代表任务真正成功。系统应以可复现的结果和环境证据作为判断依据，而不是仅凭模型自述。</small>

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>01 / Agent autonomy<br/><sub>智能体自主性</sub></h3>
      <p>Multi-step agents that plan, act, observe, recover, and adapt as the environment changes.</p><p><small>能够规划、行动、观察、恢复，并随环境变化持续调整的多步骤智能体。</small></p>
    </td>
    <td width="33%" valign="top">
      <h3>02 / Execution control<br/><sub>执行控制</sub></h3>
      <p>Explicit scope, isolated runtimes, bounded budgets, least privilege, and traceable tool use.</p><p><small>通过明确的授权范围、隔离运行时、预算限制、最小权限和可追溯工具调用控制执行过程。</small></p>
    </td>
    <td width="33%" valign="top">
      <h3>03 / Evidence-based evaluation<br/><sub>基于证据的评测</sub></h3>
      <p>Independent verifiers, reproducible tasks, structured traces, and measurable results.</p><p><small>通过独立验证器、可复现任务、结构化轨迹和可量化结果评估系统能力。</small></p>
    </td>
  </tr>
</table>

## System map

<small>系统架构</small>

```mermaid
flowchart LR
    RC["RED COPILOT<br/>AI × Offensive Security"]:::core
    EV["Red Harness<br/>Agent evaluation"]:::project
    EX["Harness Go SDK<br/>Execution + trust boundary"]:::project
    DS["ARL / red-x<br/>Attack surface discovery"]:::project
    VR["Verifier / Evaluator<br/>Authoritative result"]:::verify

    RC --> EV
    EV --> EX
    EX --> DS
    EX --> VR
    VR -. feedback .-> EV

    classDef core fill:#111113,stroke:#ff2d2d,color:#ffffff,stroke-width:2px;
    classDef project fill:#18181b,stroke:#52525b,color:#fafafa,stroke-width:1px;
    classDef verify fill:#450a0a,stroke:#ef4444,color:#fecaca,stroke-width:1px;
    linkStyle default stroke:#ef4444,stroke-width:1.5px;
```

<p align="center"><sub>Only the verifier or benchmark evaluator can close the loop.<br/>只有验证器或基准评测器才能完成最终判定并闭合反馈循环。</sub></p>

## Projects

<small>项目矩阵</small>

<table>
  <tr>
    <td width="33%" valign="top">
      <p align="center"><a href="https://github.com/red-copilot/red-copilot"><img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-red-harness.svg" width="64" alt="Red Harness icon" /></a></p>
      <h3 align="center"><a href="https://github.com/red-copilot/red-copilot">Red Harness</a><br/><sub>智能体评测与编排框架</sub></h3>
      <p align="center"><strong>EVALUATE</strong></p>
      <p>A reproducible evaluation runtime for security agents. Task contracts, isolated execution, budgets, telemetry, and authoritative verification form one closed loop.</p><p><small>面向安全智能体的可复现评测运行时，将任务契约、隔离执行、预算、遥测与权威验证整合为闭环。</small></p>
      <p><code>Python</code> <code>Docker</code> <code>Pi</code></p>
    </td>
    <td width="33%" valign="top">
      <p align="center"><a href="https://github.com/red-copilot/harness"><img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-harness-sdk.svg" width="64" alt="Harness Go SDK icon" /></a></p>
      <h3 align="center"><a href="https://github.com/red-copilot/harness">Harness Go SDK</a><br/><sub>Go 执行与信任边界 SDK</sub></h3>
      <p align="center"><strong>EXECUTE</strong></p>
      <p>A Go-native execution and trust boundary with container isolation, Pi RPC transport, SQLite audit records, and authoritative verification.</p><p><small>原生 Go 执行与信任边界，提供容器隔离、Pi RPC 通信、SQLite 审计记录与权威验证。</small></p>
      <p><code>Go</code> <code>Docker</code> <code>SQLite</code></p>
    </td>
    <td width="33%" valign="top">
      <p align="center"><a href="https://github.com/red-copilot/red-x"><img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-arl.svg" width="64" alt="ARL / red-x icon" /></a></p>
      <h3 align="center"><a href="https://github.com/red-copilot/red-x">ARL / red-x</a><br/><sub>攻击面发现与资产分析</sub></h3>
      <p align="center"><strong>DISCOVER</strong></p>
      <p>An authorization-first external attack surface management and asset reconnaissance platform with traceable assets, risk, tasks, and reports.</p><p><small>以授权为先的外部攻击面管理与资产侦察平台，支持资产、风险、任务和报告的全程追踪。</small></p>
      <p><code>Go</code> <code>React</code> <code>PostgreSQL</code></p>
    </td>
  </tr>
</table>

## Engineering principles

<small>工程原则</small>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Authorization first<br/><sub>授权优先</sub></h3>
      <p>Authorization is the starting condition, not a disclaimer. Testing stays within explicitly permitted scope.</p><p><small>授权是测试的前置条件，而不是免责声明。所有测试均限定在明确许可的范围内。</small></p>
    </td>
    <td width="50%" valign="top">
      <h3>Evidence over claims<br/><sub>证据优于自述</sub></h3>
      <p>Agent messages and tool exit codes are observations. Only a verifier or benchmark evaluator can produce a successful verdict.</p><p><small>智能体消息和工具退出码都只是观测信息；成功结论必须由验证器或基准评测器给出。</small></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Isolated by default<br/><sub>默认隔离</sub></h3>
      <p>Containers, networks, credentials, and filesystems are isolated by default. Dangerous capabilities must be explicitly enabled.</p><p><small>默认隔离容器、网络、凭据与文件系统；高风险能力必须经过显式授权才能启用。</small></p>
    </td>
    <td width="50%" valign="top">
      <h3>Reproducible by design<br/><sub>可复现设计</sub></h3>
      <p>Tasks, seeds, environments, budgets, traces, and results are auditable, replayable, and comparable.</p><p><small>任务、随机种子、环境、预算、执行轨迹和结果均应可审计、可回放、可比较。</small></p>
    </td>
  </tr>
</table>

## Enter the system

<small>开始探索</small>

<p align="center">
  <a href="https://github.com/orgs/red-copilot/repositories"><strong>Browse repositories →</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/CONTRIBUTING.md">Contribute</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/red-copilot/.github/blob/main/SECURITY.md">Security policy</a>
</p>

<p align="center">
  <strong>Build autonomous systems. Prove real outcomes.</strong>
</p>

<p align="center">
  <sub>All security testing must be limited to systems you own or are explicitly authorized to assess.<br/>所有安全测试仅限于自有系统或已获得明确授权的目标。</sub>
</p>
