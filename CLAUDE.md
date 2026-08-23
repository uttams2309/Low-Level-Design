# low-level-design

LLD practice. Repo `github.com/uttams2309/Low-Level-Design`, branch `main`.

## Two constraints the repo holds itself to — keep them

1. **Plain Java, no framework.** If Spring would have solved it, the exercise is void.
2. **Hand-written in-memory stores** rather than a database.

## Contents

- `src/fundamentals.java`
- `src/designPatterns/creationalDP/` — Singleton, FactoryMethod, AbstractFactory,
  Prototype, Builder (all five creational patterns)

Structural and behavioural patterns are **not** here — they live as separate IntelliJ
projects under `learning/design-patterns/`. Folding them in would be a reasonable
consolidation.

## Run

```sh
cd src && javac fundamentals.java && java fundamentals
```

No build tool. `out/production/` is stale IntelliJ output — gitignored, disposable.

## State

`.idea/` was tracked; untracked 2026-08-23 and gitignored. The creational-pattern work had
been sitting uncommitted since March 2026 and was committed 2026-08-23.
