<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/snowbros-lockup-paper.svg">
  <img src="assets/snowbros-lockup-ink.svg" alt="SNOWBROS" width="320">
</picture>

**Independent engineering studio. Software that holds its shape.**

Developer tools, products and interfaces that tell you what they actually did —
built on one principle: *same input in, same result out.*

[snowbros.me](https://snowbros.me) · [Start a project](https://snowbros.me/#contact) · [LinkedIn](https://www.linkedin.com/company/snowbros-studio/)

</div>

---

## What we build

We build tools that reason about code the way a compiler does — the same
input always produces the same output, every finding carries evidence, and
nothing is ever guessed. No heuristics-by-vibes, no AI in the analysis path,
no flaky results between runs.

## Projects

### 🛰️ [Atlas](https://github.com/snowbros-labs/atlas) — flagship

Deterministic static analysis for JS/TS: a resolved, project-wide **semantic
symbol model** — cross-file call graph, TypeScript type IR, import graph —
that powers real diagnostics: circular imports and type references, dead code
and unused exports, Next.js server/client boundary violations, hardcoded
secrets, broken path aliases, and more. Ships as a CLI (`sb`), a language
server, and a VS Code extension. Same codebase → identical findings,
byte-for-byte.

```sh
npx snowbros@latest analyze .
```

[![crates.io](https://img.shields.io/crates/v/snowbros-atlas?label=crates.io)](https://crates.io/crates/snowbros-atlas)
[![npm](https://img.shields.io/npm/v/snowbros?label=npm)](https://www.npmjs.com/package/snowbros)
[![VS Code](https://img.shields.io/visual-studio-marketplace/v/snowbros.snowbros-atlas?label=vs%20code)](https://marketplace.visualstudio.com/items?itemName=snowbros.snowbros-atlas)

### 🧠 [mentor-skill](https://github.com/snowbros-labs/mentor-skill)

An engineering-intelligence system for Claude Code — a capability
orchestrator that teaches or builds across software, backend, frontend,
architecture, security, design, AI, DevOps, and leadership.

### [creative-engineering](https://github.com/snowbros-labs/creative-engineering)

An agent skill and modular TypeScript toolkit for motion, scroll choreography,
interactive 3D and premium interfaces. It builds [snowbros.me](https://snowbros.me) —
see it run in [the lab](https://snowbros.me/lab.html).

### 🍺 [homebrew-tap](https://github.com/snowbros-labs/homebrew-tap)

Homebrew formulae for Snowbros Labs tools.

```sh
brew install snowbros-labs/tap/snowbros-atlas
```

## Principles

- **Deterministic.** Same codebase → identical output, sorted and stable.
- **No AI in the analysis path.** AI never decides a diagnostic.
- **No heuristic without evidence.** Every finding carries at least one.
- **Accuracy over quantity.** Unresolved ≠ guessed.

---

<div align="center">
<sub>SNOWBROS · <a href="https://snowbros.me">snowbros.me</a> · <a href="https://snowbros.me/privacy.html">Privacy</a></sub>
</div>
