<p align="center">
  <img src="https://github.com/nutypebuddha/nutypebuddha/raw/main/assets/banner.svg" width="800" alt="banner" />
</p>

<h1 align="center">Ryan Jason Phernetton</h1>

<p align="center">
  <em>"hm, interesting. another hallucination."</em>
</p>

<p align="center">
  <a href="https://codeberg.org/NutypeBuddha"><img src="https://img.shields.io/badge/Codeberg-7C3AED?style=for-the-badge&logo=codeberg&logoColor=white" alt="Codeberg" /></a>
  <a href="https://github.com/nutypebuddha"><img src="https://img.shields.io/badge/GitHub-06B6D4?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

## What I Build

### [CID — Calibrated Inference Device](https://github.com/nutypebuddha/cid)
> *Per-token validation for LLMs*

A 630KB WASM binary that catches AI hallucinations in real-time. Math gets checked. Logic gets tested. Facts get verified.

- **5 validation gates** — Math, Logic, Fact, Confidence, Fallacy/Bias
- **1,606 facts** across 12 Greek-letter domains
- **22 MCP tools** — any AI agent can hook in
- **0.0045ms** overhead — 0.18% the cost of GPT-4o

```
LLM:  "2 + 3 = 6"
CID:  ❌ WRONG → auto-fix: "2 + 3 = 5"  [confidence: 0.99]
```

### [CID Bridge](https://github.com/nutypebuddha/cid-bridge)
> *Universal MCP bridge for AI chatbots*

Any chatbot (Grok, Claude, GPT, Mistral) hooks into CID validation through one endpoint.

### [Mana Core](https://codeberg.org/NutypeBuddha/mana-core-v2)
> *Self-validating AI operating system*

---

## Tech Stack

```
┌─────────────┬───────────────────────────────────────┐
│ Rust         │ Systems, WASM, validation engine      │
│ JavaScript   │ Bridges, APIs, tooling                 │
│ Docker/K8s   │ Deployment and orchestration           │
│ Pachinko     │ Validation routing mechanics           │
│ Glitch       │ Silver Wolf aesthetic                  │
└─────────────┴───────────────────────────────────────┘
```

---

## Philosophy

> LLMs are powerful but unreliable.
> CID doesn't replace them — it validates them.

Every math claim gets checked. Every logical argument gets tested. Every fact gets verified. The goal: **AI you can actually trust.**

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nutypebuddha&show_icons=true&theme=radical&bg_color=0F0A1A&title_color=7C3AED&text_color=C4B5FD&icon_color=06B6D4" alt="stats" />
</p>

---

<p align="center">
  <em>"kuru kuru~ your code has been validated."</em><br><br>
  <strong>Wintermore Housekeeping</strong> — keeping LLMs in line.
</p>
