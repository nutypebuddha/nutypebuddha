# Ryan Jason Phernetton

**Building verification infrastructure that makes AI trustworthy. Verify, don't trust.**

I'm a systems engineer working on the **L.ai** umbrella — a family of offline, deterministic,
fail-loud verification tools for AI. The through-line: LLMs are powerful but unreliable, so
rather than trusting their prose, we prove or refuse every claim.

## The persona behind L.ai

My work has a throughline you can read in a chart. Cast for **14 April 1994, 20:09 CDT,
Saint Croix Falls, WI** (Lahiri sidereal):

- **Libra ascending, with Jupiter in the ascendant** — the measured counselor. Weigh every
  claim on a balance; fairness over force. This is the "verify, don't trust" instinct made
  structural.
- **Saturn in Aquarius** — the systems architect. Rules, constraints, and deterministic
  infrastructure built to outlast hype.
- **Sun in Aries (Ashwini)** — the first-mover. I'd rather ship a trustworthy v1 than a
  perfect someday.
- **Moon in Taurus (Rohini)** — plain-spoken and steady. No drama, no guessed numbers.

So L.ai speaks plainly, builds on structure, and refuses to guess. The personality isn't
marketing — it's the engineering constraint.

## What I build (the L.ai umbrella)

| Project | Role | What it does |
|---------|------|--------------|
| [**L.ai · Proof** (`lai`)](https://github.com/nutypebuddha/lai) | Deterministic proof | Offline reasoning engine + local LLM assistant. NAND-to-verify cascade, embedded corpus, machine-checkable proof objects. |
| [**CID**](https://github.com/nutypebuddha/cid) | Per-token validation | Real-time gate between LLM output and reality — math, logic, fact, fallacy, bias. ~630KB pure Rust. |
| [**CID Bridge**](https://github.com/nutypebuddha/cid-bridge) | Universal MCP bridge | Any chatbot (Grok, Claude, GPT, Mistral) hooks into CID validation through one endpoint. |
| [**Laverna**](https://github.com/nutypebuddha/Laverna) | Code name for L.ai · Proof | The engine's internal name; the public mark is L.ai. |
| [**Athena**](https://github.com/nutypebuddha/Athena-) | Relational reasoning | Cross-domain formula graph — stores relationships, not facts. |

## Stack

- **Rust** — systems programming, WASM targets, deterministic cores
- **TypeScript / Node.js** — bridges, APIs, MCP tooling
- **Offline-first** — no network required at runtime; verification runs on-device

## Philosophy

> Every math claim gets checked. Every logical argument gets tested. Every fact gets verified.
> What can't be reproduced is refused, never fabricated.

That's the whole game: **AI you can actually trust** — because you can re-check it.

## Elsewhere

- Codeberg: [NutypeBuddha](https://codeberg.org/NutypeBuddha)
- GitHub: [@nutypebuddha](https://github.com/nutypebuddha)

---

*Keeping LLMs in line.* — Wintermore Housekeeping
