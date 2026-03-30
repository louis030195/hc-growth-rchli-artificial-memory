# Awesome Artificial Memory [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of resources on memory systems — spanning LLMs, autonomous agents, and biological cognition — with the goal of building bridges between them.

## Why This Project?

As large language models evolve, it is becoming clear that they need more than a flat context window. They may require **multi-dimensional memory** — structurally diverse (semantic, episodic, procedural) and temporally layered (fast working memory vs. slow consolidated memory) — much like biological brains.

From the other direction, the science of cognition offers a compelling hint: **memory may be the gateway to consciousness**. Understanding how memories form, consolidate, and reconstruct could illuminate not just how to build better AI systems, but what it means to be aware at all.

This project sits at the intersection of these two currents. By mapping memory mechanisms across artificial and biological systems, we hope to:

- Inform the design of more capable and human-aligned AI memory architectures
- Surface conceptual bridges between machine learning and cognitive science
- Spark interdisciplinary curiosity about the nature of memory and mind

## Contents

- [LLM Memory](#llm-memory)
- [Agent / Harness Memory](#agent--harness-memory)
- [Biological Memory](#biological-memory)
- [Bridging Perspectives](#bridging-perspectives)

## LLM Memory

*Memory mechanisms within large language models themselves — context windows, retrieval-augmented generation, parameter-based recall, and beyond.*

> 🚧 Section under construction — contributions welcome!

## Agent / Harness Memory

*Memory architectures for autonomous agents and orchestration frameworks — scratchpads, memory banks, reflection loops, and persistent state.*

### Research & Analysis

- [Harness-Level Memory Systems for AI Coding Agents](../read/harness-memory/harness-memory-systems.md) — Comparative analysis of memory implementations across 7 coding agent harnesses (Claude Code, OpenCode, Cursor, Windsurf, Cline, Codex CLI, Aider), covering taxonomy, cross-cutting patterns, and theoretical foundations.

### Foundational Work

- [MemGPT / Letta](https://docs.letta.com/concepts/memgpt/) — OS-inspired tiered memory for LLM agents: core memory (in-context, self-editable) + archival memory (out-of-context, embedding-based retrieval). The seminal work that treats the context window as RAM and external storage as disk.
- [Building AI Coding Agents for the Terminal (arxiv 2603.05344)](https://arxiv.org/html/2603.05344v1) — Technical report on terminal-native agent architecture, including dual-memory (episodic + working), progressive compaction, cross-session playbooks, and event-driven system reminders.

### Coding Agent Implementations

- [Claude Code Memory](https://code.claude.com/docs/en/memory) — Dual system: human-written CLAUDE.md (multi-scope, path-scoped rules) + agent-written auto memory (index file with 200-line cap, topic files loaded on-demand).
- [Codex CLI AGENTS.md](https://developers.openai.com/codex/guides/agents-md) — Hierarchical instruction files (global → project → directory) with merge-order precedence, 32KiB cap, and session transcripts.
- [Windsurf Cascade Memories](https://docs.windsurf.com/windsurf/cascade/memories) — Rules (version-controlled, multi-activation-mode) + auto-generated Memories (workspace-scoped, relevance-based retrieval).
- [Cline Memory Bank](https://docs.cline.bot/features/memory-bank) — Methodology using 6 structured markdown files + `.clinerules`; community MCP server implementations for standardized memory management.
- [Aider Configuration & Conventions](https://aider.chat/docs/config.html) — Minimal memory approach: CONVENTIONS.md as read-only context + repo map for automatic context discovery.

### OpenCode Memory Plugins

- [opencode-agent-memory](https://github.com/joshuadavidthomas/opencode-agent-memory) — Letta-inspired self-editing memory blocks with persona/human/project scopes, agent tools for memory manipulation, and optional journal with local semantic search.
- [opencode-working-memory](https://github.com/sdwolf4103/opencode-working-memory) — Four-tier architecture: persistent core memory, auto-extracted working memory with exponential decay, real-time memory pressure monitoring, and storage governance.

### Memory Infrastructure

- [Cursor Memory Bank](https://www.lullabot.com/articles/supercharge-your-ai-coding-cursor-rules-and-memory-banks) — Community-driven convention using 6 structured markdown files as persistent project context for Cursor.
- [Memstate](https://memstate.ai) — External persistent, versioned memory for AI coding agents (cross-tool).
- [CodeMem](https://codemem.dev) — Permanent memory layer for coding agents across Claude Code, Cursor, and Cline.

## Biological Memory

*Insights from neuroscience and cognitive science — working memory, long-term potentiation, memory consolidation, reconsolidation, and the role of memory in consciousness.*

> 🚧 Section under construction — contributions welcome!

## Bridging Perspectives

*Work that explicitly connects artificial and biological memory — computational models of hippocampal replay, complementary learning systems theory, and memory-inspired AI architectures.*

> 🚧 Section under construction — contributions welcome!

## Contributing

Contributions are welcome! Please open an issue or submit a pull request to add resources, suggest new categories, or improve existing descriptions.

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
