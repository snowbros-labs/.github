<div align="center">

# ❄️ Snowbros Labs

**Deterministic developer tools. Same code in, same findings out.**

Engineering-intelligence tooling for JavaScript / TypeScript codebases —
built on one principle: *analysis is a compiler, not a guess.*

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
<sub>Snowbros Labs · <a href="https://snowbros.me/atlas/">snowbros.me/atlas</a></sub>
</div>
