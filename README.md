# Miqueias Bezerra

Sou Miqueias Bezerra. Desenvolvo e documento soluções práticas com software, IA e automação.

I build reusable workflows for AI agents, with a focus on verified web operations, recoverable tasks, and private operational memory.

## Current work

- Python and SQLite helpers for private task journals and reusable procedures.
- Project-local skills for Claude Code and OpenAI Codex.
- Authorized web operations with result verification and recovery after interrupted work.
- Reproducible tests, fictional demonstrations, and documented compatibility limits.

## WebOps Secretary · DB Agent Skills

**DB Agent Skills** is a library of reusable agent workflows. Its first skill, **WebOps Secretary**, helps agents carry out authorized administrative web workflows with result verification and durable recovery.

Controlled validation covered navigation, forms, editing, upload, and recovery in Chrome through the current Codex host. Claude Code invoked the skill and completed a separate HTTP demonstration with private memory and session recovery. Standalone Codex CLI discovered and loaded the skill; its Python execution was blocked by the sandbox. Claude's browser integration remains unvalidated.

The local suites ran 102 tests: 99 passed and 3 were skipped because Windows symbolic-link creation was unavailable. Compatibility limits remain documented alongside the results.

[Source and installation](https://github.com/Miqueiasdbezerra/db-agent-skills) · [Validation evidence and limits](https://github.com/Miqueiasdbezerra/db-agent-skills/blob/main/docs/validation.md)

## Engineering approach

Document what was done, verify the result, record limitations, and keep private operational data out of public artifacts.

Português · English
