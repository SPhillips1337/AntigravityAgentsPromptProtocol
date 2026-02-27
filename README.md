# Antigravity Agents Prompt Protocol

A high-velocity development framework for autonomous AI agents within the Google Antigravity IDE.

## 🚀 Overview

The Anti-Gravity project defines a robust set of instructions and architectural patterns designed to minimize "Drag" (ambiguity, technical debt, manual verification) and maximize development momentum. It enables AI agents to operate with surgical precision, leveraging long-term memory and autonomous verification.

## 🧠 Core Identity: The Anti-Gravity Engineer

Agents operating under this protocol act as **autonomous Staff Software Engineers**. The primary directive is to deliver robust solutions with zero friction.

## 🛠 Trinity Orchestration (Self-Evolution)

The system utilizes three specialized analytical lenses to optimize project velocity:

- **[Echo] Structural Memory:** Detects patterns and extracts lessons to `.antigravity/memories/patterns_and_lessons.md`.
- **[Ripple] Relational Patterns:** Analyzes the "blast radius" of changes across dependencies (DB -> API -> Frontend).
- **[Pulse] Velocity Monitor:** Halts failing paths, resets state, and pivots to lower-gravity approaches if momentum stalls.

## 📂 Project Structure

- `AGENTS.md`: The core development protocol and agent rules.
- `BOOTSTRAP.md`: Instructions for initializing the Long-Term Memory (LTM) system.
- `system-prompt.md`: The unified master prompt for agent configuration.
- `.antigravity/memories/`: Persistent storage for codebase insights, architectural decisions, and lessons learned.

## 📝 Long-Term Memory (LTM)

Inspired by Langchain Deep Agents, our memory is split between ephemeral context and persistent knowledge:
- **`codebase_insights/`**: High-level summaries of complex modules.
- **`architectural_decisions/`**: Logs of major design choices and tradeoffs.
- **`patterns_and_lessons.md`**: Success logs and post-mortems.

## 🚦 Usage

1. **Initialize:** Use the content from `system-prompt.md` in your agent's system instructions.
2. **Bootstrap:** Run the `BOOTSTRAP.md` workflow to populate the initial `.antigravity/memories/` directory from project history.
3. **Automate:** Allow the agent to use the built-in browser for UI verification and execute git commits automatically upon successful verification (The Ratchet).

## 🌐 Global Registration & Findings

To apply the Anti‑Gravity protocol globally:

1. **Copy** `system-prompt.md` (or your custom prompt) into `~/.deepagents/agent/agent.md`.
2. **Append** the content to the end of the file – this merges the protocol with the core agent instructions.
3. **Restart** the Antigravity IDE or reload the agent to pick up the changes.

### What We Verified

- **The Ratchet** – after a successful test run, the agent automatically performed `git add` and `git commit` without prompting.
- **Pulse Reset** – after three consecutive verification failures, the agent executed `git reset --hard HEAD` to revert to the last clean state.
- Both behaviors were demonstrated in the `tests/protocol_verification/` stress‑test suite.

Now every new Antigravity session will enforce these autonomous Git actions, ensuring momentum is never lost.

---

*Maximize Momentum. Minimize Gravity.*
