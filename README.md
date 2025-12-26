# Agent Rules

A unified ruleset for LLM-powered development agents. Combines behavioral guardrails, frontend standards, and a custom design language into a single configuration.

## What This Is

A structured prompt system that enforces:

- **Behavioral Protocols** — Keeps agents focused, prevents hallucination and deviation from instructions. Includes an "ULTRATHINK" deep-reasoning mode for complex problems.
- **Frontend Standards** — Anti-generic design philosophy with strict library discipline (Shadcn, Radix, MUI). Prioritizes intentional minimalism and distinctive UI.
- **Aesthetic Preferences** — A frosted-glass/acrylic design language with defined tokens, surfaces, and interaction patterns.

## Hierarchy

```
Guardrails (behavior) → Standards (foundation) → Preferences (aesthetics)
```

Part 3 applies *on top* of Part 2 — preferences dress up the standards, never override them.

## Usage

Drop the ruleset into your agent's system prompt, custom instructions, or `.cursorrules` file.

## Key Features

- Zero-fluff default mode with optional deep-analysis trigger
- Strict library-first policy (no reinventing wheels)
- Acrylic/glass design system with full token definitions
- Clear do/don't guidance to prevent common AI design pitfalls

---

*Built for agents that ship production-grade UI without the generic AI aesthetic.*
