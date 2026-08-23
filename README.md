# Low-Level-Design

Implementations of the concepts that come up in low-level design work and LLD interview
rounds.

Two rules the repo sticks to:

1. **Plain Java only** — no Spring, no framework. If a framework would have solved it,
   the exercise hasn't taught you anything.
2. **In-memory data stores** — write the storage layer by hand wherever one is needed,
   rather than reaching for a database.

## Contents

```
src/
├── fundamentals.java
└── designPatterns/
    └── creationalDP/
        ├── SingletonDP.java
        ├── FactoryMethodDP.java
        ├── AbstractFactoryDP.java
        ├── PrototypeDP.java
        └── BuilderDP.java
```

Creational patterns are done. Structural and behavioural are the gap — those live
separately in `learning/design-patterns/` as standalone IntelliJ projects, and could be
folded in here.

## Run

Plain Java, no build tool:

```sh
cd src
javac fundamentals.java && java fundamentals
javac designPatterns/creationalDP/SingletonDP.java && java designPatterns.creationalDP.SingletonDP
```

`out/production/` holds stale compiled classes from IntelliJ; it is gitignored and safe to
delete.

## Related

- `learning/lld/distributed-cache/` — a cache design exercise with written notes
- `learning/lld/gaurav-sen-lld-workspace/` — course material
- `notes/reference/LLD-Day-01-responsibility-assignment.pdf`
