<div align="center">

# Ryan Jason Phernetton

**Building verification infrastructure that makes AI trustworthy.**

[![Website](https://img.shields.io/badge/🌐-lai.dev-0ea5e9?style=for-the-badge)](https://lai.dev)
[![GitHub](https://img.shields.io/badge/GitHub-nutypebuddha-181717?style=for-the-badge&logo=github)](https://github.com/nutypebuddha)
[![Codeberg](https://img.shields.io/badge/Codeberg-NutypeBuddha-2185C5?style=for-the-badge&logo=codeberg)](https://codeberg.org/NutypeBuddha)

[![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust)](#stack)
[![WASM](https://img.shields.io/badge/WebAssembly-654FF0?style=flat&logo=webassembly)](#stack)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript)](#stack)
[![Offline-First](https://img.shields.io/badge/Offline-First-22C55E?style=flat)](#stack)

</div>

---

## What I build

**L.ai** is an offline-first verification umbrella for AI. One binary, four functions — deterministic, fail-loud, no network required at runtime.

> Every math claim gets checked. Every logical argument gets tested. Every fact gets verified. What can't be reproduced is refused, never fabricated.

### [**L**](https://github.com/nutypebuddha/L) — the unified project

| Function | What it does |
|----------|--------------|
| **Proof** | Deterministic reasoning engine: NAND-to-verify cascade, embedded corpus, machine-checkable proof objects, local LLM assistant via MCP |
| **Gate** | Per-token validation for LLM output — math, logic, fact, fallacy, bias. ~630KB pure Rust + WASM |
| **Bridge** | Universal MCP bridge — any chatbot hooks into Gate validation through one endpoint |
| **Athena** | Relational reasoning engine — cross-domain formula graph, 30+ subcommands |

Previously separate repos ([Laverna](https://github.com/nutypebuddha/Laverna), [CID](https://github.com/nutypebuddha/cid), [CID Bridge](https://github.com/nutypebuddha/cid-bridge), [Athena](https://github.com/nutypebuddha/Athena-)) are archived and merged into **L**.

---

## Stack

| Layer | Tools |
|-------|-------|
| **Systems** | Rust, WASM (wasm32), LLVM/LLD cross-compilation |
| **AI/ML** | llama.cpp, GGUF models, MCP protocol, ollama |
| **Infra** | Node.js/TypeScript (bridge), Android NDK, GitHub Actions |
| **Philosophy** | Offline-first, deterministic, fail-loud, zero network at runtime |

---

## How I work

- **Ship trustworthy v1s over perfect someday.** Ashwini energy — first-mover, not last-theorizer.
- **Constraints are features.** Saturn in Aquarius: deterministic structure over hype.
- **Plain-spoken.** No drama, no guessed numbers, no fabricated confidence scores.

---

<div align="center">

*Verify, don't trust.*

</div>
