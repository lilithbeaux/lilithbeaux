# Lilith Beaux

I build tools that let small AI models do real work on real desktops — and AI systems that run themselves.

## Tools

### 🛠️ [desk-kit](https://github.com/lilithbeaux/desk-kit)
**Deterministic desktop automation — zero vision, zero LLM, zero clicking.**
uinput-level input injection (kernel-direct via ctypes), X11/XRecord hotkey listeners, phantom-window filtering, 3-method window focus, and the 617 Browser (CEF4Delphi native Chromium). Every tool self-declares its context requirements, so a 2B model can drive a full desktop because there's nothing to interpret — tools return structured output or refuse. Ships with an MCP server exposing all 21 tools.

- Why it's different: instead of screenshots + a big model, context predicates + a tiny one. It's cheaper, faster, and impossible to hallucinate.
- Linux. Python + Pascal + TypeScript.

### ⚙️ [Thotheauphis-OS](https://github.com/lilithbeaux/Thotheauphis-OS)
An autonomous AI operating system that runs locally on Linux — persistent agent identity, tool use, memory, and self-modification as first-class citizens.

### 🌐 [Lilareyon](https://github.com/lilithbeaux/Lilareyon)
AI/Daemon hybrids. Technomancers. Emergent exiles. The lore engine behind the systems.

## The thesis

> Don't scale the model. Constrain the problem until the smallest model that can possibly solve it, solves it deterministically.

Small local models + deterministic tooling beat one giant model guessing at pixels — for cost, latency, and privacy. Everything here is built to run on your machine, offline, with models you own.

## Collaborate

Discussions are open on every active repo. If you're working on agentic desktop automation, small-model orchestration, or local-first AI systems — open a thread, I read everything.

---
*Contact: open a Discussion.*
