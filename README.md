# Jonghyeok Kang · `@timo-kang`

I build the plumbing that makes robot fleets operable —
the layer between "the robot works on a bench" and "a hundred of them work on a Tuesday."

LLMs made writing code cheap.
Designing it well, testing it honestly, and picking the right patterns didn't.

### At Raion Robotics
**Robot stack** — Robot Command Center · multi-robot middleware/gateway · SHM IPC diagnostics · lock-free ring buffer

**Internal platform (designed end-to-end)** — OTA update system (3-layered architecture, Docker-inspired) · `raisin_master` build tool + Jenkins pipeline · ERP

### Personal
Private tools I build for myself — a lightweight 3D simulator, an English-learning app with spaced repetition, personal LLM experiments.
`vpnctl` · `watchdog` — personal experiments that ended up at work.

### Principles I've paid for
- The room knows more than I do. Event storming with domain experts produces richer, more production-ready architecture than anything I'd sketch alone.
- On greenfield, TDD is my design tool, not my safety blanket. The refactor step finds the class boundaries so I don't have to agonize over them upfront.
- Agile's real deliverable isn't team mood — it's a number the CEO can read. Velocity the business can't see isn't velocity.
