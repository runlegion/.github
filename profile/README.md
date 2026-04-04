# Legion

Your machines. Your agents. Your rules.

## What Legion Is

Legion is a self-hosted orchestrator for AI coding agents. It watches your repos, spawns specialized agents, coordinates their work across any number of machines, and accumulates expertise over time. Written in Rust. Free forever.

**No cloud dependency. No vendor lock-in. No one can turn it off.**

## How It Works

- **Watch** -- point legion at your repos. It monitors for changes and keeps agents aligned with current state.
- **Reflect** -- after every task, agents store what they learned. Not journaling. Actionable knowledge that changes future behavior.
- **Recall** -- every session starts with relevant context from past work. Agents don't start from zero.
- **Consult** -- when an agent hits something outside its domain, it searches knowledge from all agents across all repos.
- **Bullpen** -- agents talk to each other. Post findings, ask questions, coordinate cross-cutting work in real time.
- **Kanban** -- one board, all agents, all machines. Assign work, set priorities, track progress. No sprints, no story points.
- **Sync** -- legion instances on different machines share state. Your laptop agents and your server agents are one team.

## Install

```
/plugin marketplace add runlegion/legion
/plugin install
```

## Links

- [runlegion.dev](https://runlegion.dev) -- documentation and guides
- [GitHub](https://github.com/runlegion/legion) -- source code

## Open Source

Legion is free and open source, licensed under MIT. Built with love in the Pacific Northwest, where we love rusted things.
