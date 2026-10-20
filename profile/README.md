<p align="center">
  <img src="https://raw.githubusercontent.com/red-copilot/.github/main/assets/red-copilot-banner.svg" alt="Red Copilot — AI × Offensive Security" width="100%" />
</p>

<h2 align="center">AI × Offensive Security</h2>

<p align="center">
  <strong>Autonomous agents. Isolated execution. Verified outcomes.</strong>
</p>

---

## What we build

Red Copilot works at the intersection of AI and offensive security: autonomous agents that plan multi-step tasks, use security tools, understand attack surface, and produce verifiable results within explicit authorization boundaries.

We focus on the system around the model—not just the prompt. Reliable offensive-security agents need **execution boundaries, tool feedback, state tracking, budget control, and authoritative verification**.

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>01 / Autonomy</h3>
      <p>Agents that plan, act, observe, and adapt instead of following a fixed one-shot workflow.</p>
    </td>
    <td width="33%" valign="top">
      <h3>02 / Trust</h3>
      <p>Isolated execution, least privilege, audit records, and independent verification constrain every action.</p>
    </td>
    <td width="33%" valign="top">
      <h3>03 / Surface</h3>
      <p>Assets, exposure, risk, and tasks connected into a traceable context for offensive decisions.</p>
    </td>
  </tr>
</table>

## Three layers

```text
                    ┌─────────────────────────┐
                    │       RED COPILOT       │
                    │  AI × OFFENSIVE SECURITY│
                    └────────────┬────────────┘
                                 │
          ┌──────────────────────┼──────────────────────┐
          │                      │                      │
   ┌──────▼──────┐        ┌──────▼──────┐        ┌──────▼──────┐
   │   EVALUATE  │        │   EXECUTE   │        │   DISCOVER  │
   │ Red Harness │        │ Harness SDK │        │  ARL/red-x  │
   └─────────────┘        └─────────────┘        └─────────────┘
      Agent evals          Trust boundary         Attack surface
```

## Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <p><strong>EVALUATE</strong></p>
      <h3><a href="https://github.com/red-copilot/red-copilot">Red Harness</a></h3>
      <p>A reproducible evaluation runtime for security agents. Task contracts, isolated execution, budgets, telemetry, and authoritative verification form one closed loop.</p>
      <p><code>Python</code> <code>Docker</code> <code>Pi</code></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>EXECUTE</strong></p>
      <h3><a href="https://github.com/red-copilot/harness">Harness Go SDK</a></h3>
      <p>A Go-native execution and trust boundary with container isolation, Pi RPC transport, SQLite audit records, and authoritative verification.</p>
      <p><code>Go</code> <code>Docker</code> <code>SQLite</code></p>
    </td>
    <td width="33%" valign="top">
      <p><strong>DISCOVER</strong></p>
      <h3><a href="https://github.com/red-copilot/red-x">ARL / red-x</a></h3>
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
