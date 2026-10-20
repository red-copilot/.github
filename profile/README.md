<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" />
    <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner-light.svg" alt="Red Copilot — AI × Offensive Security" width="100%" />
  </picture>
</p>

<h2 align="center">AI-Native Offensive Security Engineering</h2>

<p align="center">
  <strong>Autonomy needs control. Results need evidence.</strong>
</p>

<p align="center">
  <kbd>PLAN</kbd>&nbsp;&nbsp;→&nbsp;&nbsp;
  <kbd>EXECUTE</kbd>&nbsp;&nbsp;→&nbsp;&nbsp;
  <kbd>OBSERVE</kbd>&nbsp;&nbsp;→&nbsp;&nbsp;
  <kbd>VERIFY</kbd>
</p>

---

## What we build

Red Copilot engineers reliable AI systems for offensive security. We build the infrastructure around the model: execution boundaries, tool feedback, state tracking, budget control, observability, and independent verification.

**A convincing agent response is not proof of success.** Systems should be judged by reproducible outcomes and evidence from the environment—not by the model’s claims alone.

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>01 / Agent autonomy</h3>
      <p>Multi-step agents that plan, act, observe, recover, and adapt as the environment changes.</p>
    </td>
    <td width="33%" valign="top">
      <h3>02 / Execution control</h3>
      <p>Explicit scope, isolated runtimes, bounded budgets, least privilege, and traceable tool use.</p>
    </td>
    <td width="33%" valign="top">
      <h3>03 / Evidence-based evaluation</h3>
      <p>Independent verifiers, reproducible tasks, structured traces, and measurable results.</p>
    </td>
  </tr>
</table>

## System map

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

<p align="center"><sub>Only the verifier or benchmark evaluator can close the loop.</sub></p>

## Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <p align="center"><a href="https://github.com/red-copilot/red-copilot"><img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-red-harness.svg" width="64" alt="Red Harness icon" /></a></p>
      <h3 align="center"><a href="https://github.com/red-copilot/red-copilot">Red Harness</a></h3>
      <p align="center"><strong>EVALUATE</strong></p>
      <p>A reproducible evaluation runtime for security agents. Task contracts, isolated execution, budgets, telemetry, and authoritative verification form one closed loop.</p>
      <p><code>Python</code> <code>Docker</code> <code>Pi</code></p>
    </td>
    <td width="33%" valign="top">
      <p align="center"><a href="https://github.com/red-copilot/harness"><img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-harness-sdk.svg" width="64" alt="Harness Go SDK icon" /></a></p>
      <h3 align="center"><a href="https://github.com/red-copilot/harness">Harness Go SDK</a></h3>
      <p align="center"><strong>EXECUTE</strong></p>
      <p>A Go-native execution and trust boundary with container isolation, Pi RPC transport, SQLite audit records, and authoritative verification.</p>
      <p><code>Go</code> <code>Docker</code> <code>SQLite</code></p>
    </td>
    <td width="33%" valign="top">
      <p align="center"><a href="https://github.com/red-copilot/red-x"><img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/project-arl.svg" width="64" alt="ARL / red-x icon" /></a></p>
      <h3 align="center"><a href="https://github.com/red-copilot/red-x">ARL / red-x</a></h3>
      <p align="center"><strong>DISCOVER</strong></p>
      <p>An authorization-first external attack surface management and asset reconnaissance platform with traceable assets, risk, tasks, and reports.</p>
      <p><code>Go</code> <code>React</code> <code>PostgreSQL</code></p>
    </td>
  </tr>
</table>

## Engineering principles

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Authorization first</h3>
      <p>Authorization is the starting condition, not a disclaimer. Testing stays within explicitly permitted scope.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Evidence over claims</h3>
      <p>Agent messages and tool exit codes are observations. Only a verifier or benchmark evaluator can produce a successful verdict.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Isolated by default</h3>
      <p>Containers, networks, credentials, and filesystems are isolated by default. Dangerous capabilities must be explicitly enabled.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Reproducible by design</h3>
      <p>Tasks, seeds, environments, budgets, traces, and results are auditable, replayable, and comparable.</p>
    </td>
  </tr>
</table>

## Enter the system

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
  <sub>All security testing must be limited to systems you own or are explicitly authorized to assess.</sub>
</p>
