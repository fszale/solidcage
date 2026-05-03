# solidcage

Public mirror of the marketing pages and shared brand assets for
[**SolidCage**](https://solidcage.com), the agentic-OS practice of
[Filip Szalewicz](https://solidcage.com).

This repo holds the static landing pages, signature, and shared brand assets
that pair with the open-source agentic-OS toolchain. The interactive surfaces
(twin portal, ROI tools, OI tracker, decks) live in their own repos and are
served from a single Replit Deployment.

## Live tools

All SolidCage tools and decks ship from a single Replit Deployment. Replace
`<DEPLOY_URL>` below with the live `*.replit.app` host from the project's
Publishing tool, or with the configured custom domain (e.g.
`apps.solidcage.com`):

| Surface | Path | Source repo |
| --- | --- | --- |
| Digital Twin Factory Demo Portal | `<DEPLOY_URL>/twin-portal/` | [`digital-twin-factory`](https://github.com/fszale/digital-twin-factory) |
| Twin Builder Wizard | `<DEPLOY_URL>/twin-portal/twin-builder` | [`agent-kernel`](https://github.com/fszale/agent-kernel) |
| Agent Factory Admin Dashboard | `<DEPLOY_URL>/twin-portal/admin` | [`agent-factory`](https://github.com/fszale/agent-factory) |
| Agent ROI Generator | `<DEPLOY_URL>/agent-roi-generator/` | [`agent-roi-generator`](https://github.com/fszale/agent-roi-generator) |
| Agentic Readiness Scorecard | `<DEPLOY_URL>/agent-roi-generator/scorecard` | [`agent-roi-generator`](https://github.com/fszale/agent-roi-generator) |
| OI Lab Rate-of-Improvement Tracker | `<DEPLOY_URL>/oi-tracker/` | [`operational-intelligence-lab`](https://github.com/fszale/operational-intelligence-lab) |
| The Agentic OS Playbook (deck) | `<DEPLOY_URL>/decks/agentic-os-playbook` | private workspace |
| The ROI of AI Employees (deck) | `<DEPLOY_URL>/decks/roi-ai-employees` | private workspace |
| Digital Twin Factories (deck) | `<DEPLOY_URL>/decks/digital-twin-factories` | private workspace |
| API Server | `<DEPLOY_URL>/api/healthz` | private workspace |

## Brand

The shared brand tokens and components used across every surface above live in
the `lib/brand` workspace package of the SolidCage Replit project
(`@workspace/brand`). Highlights:

- **Palette** — cream `#F4F1EC` background, deep navy `#0E1320` text, warm
  orange `#EB6928` primary, steel blue `#387CBD` accent.
- **Typography** — Fraunces (display, serif) + Inter (body) + JetBrains Mono
  (data / code).
- **Radii** — soft `1rem` corners, NotebookLM-inspired ambient gradients.
- **Components** — `ArtifactSwitcher` (cross-app dropdown), `BrandFooter`
  (shared credit/links), `BackToPortal` (slide-deck affordance).

## Sibling repos

- [`agentic-playbook`](https://github.com/fszale/agentic-playbook) — front
  door, audience-specific reading order
- [`agent-kernel`](https://github.com/fszale/agent-kernel) — methodology +
  twin-builder
- [`agent-factory`](https://github.com/fszale/agent-factory) — runtime + HITL
- [`digital-twin-filip`](https://github.com/fszale/digital-twin-filip) —
  reference twin
- [`digital-twin-factory`](https://github.com/fszale/digital-twin-factory) —
  demo portal
- [`agent-roi-generator`](https://github.com/fszale/agent-roi-generator) —
  ROI + readiness intake
- [`operational-intelligence-lab`](https://github.com/fszale/operational-intelligence-lab) —
  rate-of-improvement tracker

## Want it done for you?

If you would rather have an agentic OS designed and operated by the person who
built the methodology, book Filip at <https://solidcage.com>.
