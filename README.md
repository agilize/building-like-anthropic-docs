# Building Like Anthropic

A deep study guide on how Anthropic's engineering teams build software — covering development workflows, agent harness design, CLAUDE.md system, context engineering, safety research, and more.

**Live:** [building-like-anthropic.vercel.app](https://building-like-anthropic.vercel.app)

## What's Inside

| Section | Topics |
|---------|--------|
| **Philosophy** | 6 core design principles (minimal scaffolding, tool design > prompts, separate generation from evaluation) |
| **Tech Stack** | TypeScript, React+Ink, Bun, CommanderJS, Coder for remote dev |
| **Workflows** | Autonomous Loop, Slot Machine, TDD with Claude, Multi-Agent map-reduce |
| **Harnesses** | Two-agent, three-agent, and parallel agent architectures with diagrams |
| **CLAUDE.md** | 5-scope file hierarchy, hooks system (26 events), skills (SKILL.md) |
| **Boris's Setup** | Creator of Claude Code's exact daily workflow and tooling |
| **Context Engineering** | Compaction, sub-agent delegation, extended thinking, prompt caching |
| **Evals** | pass@k, pass^k, infrastructure noise, Terminal-Bench methodology |
| **Team Practices** | How 10 Anthropic teams use Claude Code (from official 22-page PDF) |
| **SDK & Agents** | Agent SDK (Python/TypeScript), subagent types, computer use |
| **MCP** | Model Context Protocol architecture, transports, ecosystem |
| **Safety** | Constitutional AI, Sleeper Agents, alignment faking, interpretability |
| **Infrastructure** | Multi-cloud (AWS/GCP), EKS ultra scale, progressive delivery, sandboxing |
| **Study Timeline** | 12-week phased adoption plan with linked resources |
| **Academy** | 8 free Anthropic courses, 6 webinars, GitHub learning repos |
| **References** | 120+ official sources (23 blog posts, 23 arxiv papers, model cards, docs) |

## Sources

All content is compiled from official, verifiable sources:

- [Anthropic Engineering Blog](https://www.anthropic.com/engineering) (23 posts)
- [Anthropic Research](https://www.anthropic.com/research) (60+ papers)
- [Transformer Circuits Thread](https://transformer-circuits.pub/) (25+ publications)
- [Claude Code Documentation](https://code.claude.com/docs)
- [How Anthropic Teams Use Claude Code (PDF)](https://www-cdn.anthropic.com/58284b19e702b49db9302d5b6f135ad8871e7658.pdf)
- Podcasts and interviews with Boris Cherny, Dario Amodei, and other Anthropic engineers

## Related

- [Claude Code para Engenheiros](https://cccourses.vercel.app/) — Hands-on course (29 modules, 100% practical)

## License

MIT
