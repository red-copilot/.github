# Red Copilot Brand & Repository Metadata

> **Security Engineering for the Agentic Era · 面向智能体时代的安全工程**

## Positioning

Red Copilot builds engineering systems for security agents that can act without becoming unaccountable. Our identity should communicate controlled execution, observable behavior, and independently verifiable outcomes—not generic cyber imagery.

**Core message:** From Agent Actions to Verifiable Outcomes.

**核心表达：** 从智能体行动，到可验证的结果。

**Primary audience:** developers, security engineers, researchers, and technical partners evaluating or contributing to Red Copilot systems.

## Signal Editorial

The visual system is **Signal Editorial**: warm paper-like surfaces, direct typography, precise rules, and a signal-red checkpoint. It should feel like a well-engineered field note, not a movie-style hacking interface.

- Prefer evidence-chain diagrams, coordinates, checkpoints, and measured whitespace.
- Avoid radar sweeps, glowing shields, generic locks, terminal rain, and decorative gradients.
- Keep English as the primary headline language and place Chinese support copy directly below it.
- Static assets are the default. Motion is not part of the core identity.

## Color tokens

| Token | Value | Use |
|---|---|---|
| Cream | `#F6F2E9` | Primary light surface and reversed text on dark surfaces |
| Ink | `#161719` | Primary light-theme text and dark graphic nodes |
| Light Red | `#C92B20` | Brand red and small text on cream/white surfaces |
| Dark Red | `#FF5A4E` | Brand red and small text on dark surfaces |
| Zinc | `#706A63` | Secondary text on cream |
| Rule | `#D3CCBF` | Borders and evidence-grid lines on light surfaces |
| Dark Surface | `#08090B` | Primary dark-theme background |
| Dark Panel | `#111214` | Raised dark panels and diagram fields |

Accessibility checks:

- `#C92B20` on `#F6F2E9`: **4.88:1**
- `#FF5A4E` on `#08090B`: **6.47:1**
- `#161719` on `#F6F2E9`: **16.06:1**
- `#706A63` on `#F6F2E9`: **4.78:1**
- `#B8B2A7` on `#08090B`: **9.45:1**

Do not use Light Red for small text on dark surfaces or Dark Red for small text on cream surfaces.

## Typography

- **Display and body:** Ubuntu Sans, then Helvetica Neue, Arial, and sans-serif fallbacks.
- **Labels and technical metadata:** Ubuntu Sans Mono, then SFMono-Regular, Consolas, and monospace fallbacks.
- **Chinese:** Noto Sans CJK SC, then PingFang SC, Microsoft YaHei, and sans-serif fallbacks.
- Use heavy display weights for short statements and wide tracking for machine labels.
- GitHub README prose uses GitHub's own typography. Exact brand typography is carried by SVG assets and exported brand material.

## Brand mark

The mark is a **checkpoint**: a signal-red rounded square, a cream routed path, and a dark result node.

- Use `assets/red-copilot-mark.svg` without recoloring.
- Keep clear space equal to at least one-quarter of the mark's width.
- Minimum digital size is 24 × 24 px.
- The mark should remain legible on both Cream and Dark Surface backgrounds.
- Do not add a shield, glow, outline, gradient, or additional character to the mark.

## Banner system

| Asset | Theme | Use |
|---|---|---|
| `assets/red-copilot-banner.svg` | Light | Shared project README banner and light organization profile |
| `assets/red-copilot-banner-dark.svg` | Dark | Organization profile when `prefers-color-scheme: dark` |

- Both banners are 1600 × 480 and use the same content hierarchy.
- `assets/red-copilot-banner.svg` is a compatibility path used by the three core project READMEs. Do not rename or remove it.
- Project marks in `assets/project-*.svg` also retain their existing paths.
- Use `<picture>` with light and dark sources in organization-facing Markdown; always include a meaningful `<img>` fallback and `alt` text.
- Do not reintroduce the retired GIF or animated SVG pipeline.

## README surfaces

- **Organization profile (`profile/README.md`):** brand-led entry point. Lead with positioning, then the three systems, the engineering control loop, and participation paths.
- **Repository home (`README.md`):** concise engineering-resource index. Explain what lives here, link to the organization profile, and keep the README standards and shared presentation rules.

Every project README should answer four questions quickly:

1. What is it?
2. What works today?
3. How do I start?
4. Where are the authoritative details?

## Writing and presentation

- English first, Chinese directly below. Keep the two versions aligned in meaning and emphasis.
- State implemented capabilities separately from limitations and plans.
- Lead with concrete nouns and verifiable claims. Avoid "revolutionary", "fully autonomous", and unsupported superlatives.
- Use badges sparingly; every badge must be factual, current, and verifiable.
- Do not claim tests passed unless they were run.
- Explain authorization boundaries, credentials, isolation, failure modes, and known limitations.
- End security-facing material with the authorized-use notice where appropriate.

## Image accessibility

- Every informative Markdown image needs concise English-first `alt` text that identifies the brand or capability shown.
- Decorative project-mark images beside a text heading may use empty `alt=""`.
- SVG files must include `<title>` and, where useful, `<desc>`.
- Do not rely on color alone to distinguish steps, states, or outcomes.
- Keep text inside diagrams at a size that remains readable when the asset is displayed at 900–1200 px wide.

## Repository descriptions

Use concise English descriptions in GitHub's repository **About → Description** field.

| Repository | Description |
|---|---|
| red-copilot | Reproducible execution and evaluation runtime for security agents, with isolated execution, world state, budgets, and independent verification. |
| harness | Go-native security agent runtime and SDK with container isolation, execution budgets, SQLite auditing, and verifier-controlled outcomes. |
| red-x | ARL 3.0 — authorization-first external attack surface management and asset reconnaissance, built with Go and React. |
| .github | Red Copilot organization profile, shared branding, community health files, and engineering standards. |

## Suggested topics

Topics are discovery metadata, not a replacement for the repository description. Keep them relevant to implemented capabilities.

- **Python Runtime:** ai-agents, agent-runtime, cybersecurity, benchmark, python
- **Go SDK:** ai-agents, agent-harness, cybersecurity, golang, sandbox
- **ARL 3.0:** attack-surface-management, asset-discovery, easm, golang, react

## Repository identity

- **red-copilot:** Red Harness Python Runtime — reproducible agent execution and evaluation.
- **harness:** Red Harness Go SDK — Go-native execution and trust boundary.
- **red-x:** ARL 3.0 — authorized asset reconnaissance and EASM.

Keep the distinction explicit; the Python runtime and Go SDK are separate implementations, not interchangeable packaging of the same runtime.

## Exported brand material

Organization avatars and social previews are uploaded separately from README content and are not generated by this repository.

When exporting manually:

- Avatar: render `assets/red-copilot-mark.svg` on a square canvas.
- Social preview: use the Signal Editorial banner hierarchy at 1280 × 640 with generous safe margins.
- Keep the headline **From Agent Actions to Verifiable Outcomes** and the supporting line **Security Engineering for the Agentic Era · 面向智能体时代的安全工程**.
