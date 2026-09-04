# Hi, I'm Abidit Shrestha 👋

**Full-Stack Product Engineer** who ships production web apps and the AI/LLM agent infrastructure behind them.

~4 years building user-facing products (most recently at Programiz, serving 1.5M+ learners). I work across the stack in **React, Next.js, TypeScript, Node.js and .NET**, and I specialize in **applied LLM systems** — multi-agent orchestration, the Model Context Protocol (MCP), prompt engineering, and eval design.

📍 Kathmandu, Nepal — **open to Dubai/UAE relocation and remote roles.**

## MCP Servers & Agent Infrastructure

[![npm](https://img.shields.io/npm/v/esewa-mcp.svg?label=esewa-mcp)](https://www.npmjs.com/package/esewa-mcp)
[![npm](https://img.shields.io/npm/v/khalti-mcp.svg?label=khalti-mcp)](https://www.npmjs.com/package/khalti-mcp)
[![npm](https://img.shields.io/npm/v/phi-guard-mcp.svg?label=phi-guard-mcp)](https://www.npmjs.com/package/phi-guard-mcp)
[![PyPI](https://img.shields.io/pypi/v/abitree.svg?label=abitree)](https://pypi.org/project/abitree/)

| Project | What it does | Tech | Package / Demo | License |
|---|---|---|---|---|
| **[eSewa MCP](https://github.com/Abidit/eSewa-Khalti-mcp)** | Nepal's first MCP server for eSewa payments — HMAC-SHA256 signed requests. | TypeScript, `@modelcontextprotocol/sdk` | [npm](https://www.npmjs.com/package/esewa-mcp) | MIT |
| **[Khalti MCP](https://github.com/Abidit/eSewa-Khalti-mcp)** | Nepal's first MCP server for Khalti payments — same monorepo as eSewa MCP. | TypeScript, `@modelcontextprotocol/sdk` | [npm](https://www.npmjs.com/package/khalti-mcp) | MIT |
| **[phi-guard-mcp](https://github.com/Abidit/phi-guard-mcp)** | Local-first MCP server that catches PHI (protected health info) flowing into LLM prompts, logs, and analytics calls, before it ships. | TypeScript, `@modelcontextprotocol/sdk`, zod | [npm](https://www.npmjs.com/package/phi-guard-mcp) | MIT |
| **[manifest-mcp](https://github.com/Abidit/manifest-mcp)** | GitHub App that reviews MCP server config changes in PRs against a 12-rule risk engine, gated by an approval workflow. | TypeScript, Probot, GitHub Actions | [Repo](https://github.com/Abidit/manifest-mcp) | — |
| **[DataHub Navigator](https://github.com/Abidit/datahub-navigator)** | Conversational, animated data-lineage explorer. Real DataHub MCP integration with a deterministic (no-LLM) graph traversal engine. Built for DataHub Agent Hackathon 2026. | Next.js 16, React 19, React Flow, Framer Motion | [Live demo](https://datahub-navigator.vercel.app) | — |
| **[Sequirly](https://github.com/Abidit/sequirly)** | Browser extension preventing PII leaks into AI chat prompts. Founding engineer: fetch interceptor, redaction engine, fail-open safety design. | TypeScript, browser extension (Vite/ESM) | [Live product](https://sequirly.com) | — |

Plus: an 8-agent Python orchestrator (review-gate pattern) used to generate 200 courses in 3 months at 10x velocity, and GPT-4o/mini hint systems with confidence-thresholded hallucination suppression shipped to 1.5M+ learners.

## Personal Builds

Live, deployed products I designed and shipped end-to-end:

| Project | What it does | Tech | Link |
|---|---|---|---|
| **[EduShip](https://eduship.dev)** | Production-ready Next.js boilerplate for EdTech platforms — auth, course/lesson system, MCQ quiz engine, certificate generation, payments, pre-wired. | Next.js 16, TypeScript, Tailwind, Clerk, Supabase, Drizzle ORM, Lemon Squeezy | [eduship.dev](https://eduship.dev) |
| **[SpectaSnap](https://spectasnap-orpin.vercel.app)** | Browser-native AR glasses try-on for optical retailers — no app install, webcam-based, with AI style recommendations. | Next.js, MediaPipe, Three.js, Claude AI | [Live demo](https://spectasnap-orpin.vercel.app) |
| **[NomadWifi](https://nomadwifi.vercel.app)** | Map-based platform to find and share WiFi spots — filter by speed, noise level, power availability. | Next.js, Supabase, Leaflet | [Live demo](https://nomadwifi.vercel.app) |
| **[Anatomly](https://anatomly.vercel.app)** | Interactive 3D map of the human body — explore organs, understand diseases and treatments. *(Early/experimental build.)* | React, Three.js, GSAP | [Live demo](https://anatomly.vercel.app) |
| **[SpeedBlip](https://speedblip.netlify.app)** | Real-time internet speed monitor for developers — live charts, threshold alerts, auto-scheduler, PWA. | React, Vite, Recharts | [Live demo](https://speedblip.netlify.app) |

## Dev Tools

[![PyPI downloads](https://img.shields.io/pypi/dm/abitree.svg)](https://pypi.org/project/abitree/)
[![License: MIT](https://img.shields.io/pypi/l/abitree.svg)](https://github.com/Abidit/abitree/blob/main/LICENSE)

- 🌳 **[abitree](https://github.com/Abidit/abitree)** — generate beautiful, icon-rich file trees for your README, instantly. Published to [PyPI](https://pypi.org/project/abitree/) and Homebrew, MIT licensed.

## Open Source

- 🔓 Reviewed, merged contribution to Meta's [`facebook/astryx`](https://github.com/facebook/astryx/pull/5321) (WCAG AA contrast fix, CLA signed).

## Stack

TypeScript · React · Next.js · Node.js · .NET · Python · MCP · PostgreSQL · Supabase · AWS

## Reach me

📫 [LinkedIn](#) · abistha01@gmail.com
