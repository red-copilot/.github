<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" />
    <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" alt="Red Copilot — Security Engineering for the Agentic Era" width="100%" />
  </picture>
</p>

<p align="center">
  <strong>Security Engineering for the Agentic Era</strong>
  <br/>
  <sub>面向智能体时代的安全工程</sub>
</p>

<h1 align="center">From Agent Actions to Verifiable Outcomes</h1>
<p align="center"><strong>从智能体行动，到可验证的结果</strong></p>

<p align="center">
  We build engineering systems that make security agents controllable, observable, and verifiable.
  <br/>
  <sub>我们构建可控、可观测、可验证的安全智能体工程系统。</sub>
</p>

<p align="center">
  <code>Plan</code> → <code>Execute</code> → <code>Observe</code> → <code>Verify</code>
  <br/>
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

### Red Harness
<sub>安全智能体执行与评测框架</sub>

Red Harness explores reproducible execution for security agents. Its engineering work separates task definitions, agent execution, target environments, model and tool access, budgets, telemetry, and verification.

<sub>Red Harness 面向安全智能体的可复现执行与评测，将任务定义、智能体运行、目标环境、模型与工具访问、预算、遥测和结果验证拆分为清晰的工程边界。</sub>

Current implementations include a Python-based evaluation runtime and a Go-native SDK. They are separate implementations with different integration contracts.

<sub>目前包含 Python 评测运行时与 Go 原生 SDK 两条实现路线；两者是独立实现，接口与集成方式并不相同。</sub>

### ARL · Asset Reconnaissance Lighthouse
<sub>资产侦察灯塔</sub>

ARL is an external attack surface management and asset reconnaissance platform for authorized security testing. It organizes organizations, domains, assets, findings, and tasks into a traceable workflow.

<sub>ARL 面向已授权安全测试，围绕组织、域名、资产、风险与任务构建可追溯的外部攻击面管理和资产侦察流程。</sub>

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
