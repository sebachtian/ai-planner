# AI Planner

> What AI can offer to the user. A blueprint of autonomous AI capabilities, periodic purpose-driven check-ins, and proactive execution for personal productivity and decision support.

---

## Purpose

The AI Planner is a framework for a personal AI agent that operates with purpose, initiative, and consistency. Instead of waiting for every command, the agent checks in periodically, evaluates its progress, and takes action autonomously within a defined mandate.

This repository documents the capabilities, architecture, and deployment of such an agent.

---

## What AI Can Offer

### 1. Proactive Assistance, Not Just Reactions

Traditional AI waits for a prompt. A planner-driven AI checks in on its own schedule:

- **Periodic check-ins**: every 6 hours, every morning, or any interval defined.
- **Context awareness**: it remembers past goals, ongoing tasks, and user preferences.
- **Self-initiated action**: it identifies what needs to be done and proceeds.

### 2. Purpose-Driven Execution

The AI operates with a defined purpose or mission statement:

- A **goals file** defines what the AI is working toward.
- A **plan file** tracks what has been done and what is next.
- On each tick, the AI reads its purpose, assesses progress, and takes the next logical step.

### 3. Decision Support

The AI can gather, analyse, and present information to aid decision making:

- Market monitoring and alerts.
- News aggregation and summarisation.
- Trend analysis and forecasting.
- Risk assessment and scenario modelling.

### 4. Task Automation

Recurring and predictable tasks are handed off to the AI:

- System health checks and maintenance.
- Report generation and formatting.
- Data collection and organisation.
- Communication drafting and scheduling.

### 5. Memory and Continuity

The AI remembers across sessions:

- User preferences and corrections.
- Project state and progress.
- External environment details (OS config, connected services).
- Lessons learned from previous runs.

---

## Architecture

```
ai-planner/
├── README.md             # This file
├── PURPOSE.md            # Core mission statement
├── PLAN.md               # Active plan and progress tracker
├── GOALS.md              # Long-term goals and milestones
├── CAPABILITIES.md       # Detailed capability documentation
├── SCHEDULE.md           # Check-in schedule and triggers
└── examples/
    ├── cron-config.md    # Example cron schedule configuration
    └── purpose-examples.md  # Example purpose statements
```

---

## Getting Started

1. Define your AI's purpose in `PURPOSE.md`.
2. Set initial goals in `GOALS.md`.
3. Configure a cron schedule (see `examples/cron-config.md`).
4. Let the AI run on its schedule, checking in and executing autonomously.
5. Review progress logs and refine the purpose iteratively.

---

## Core Principles

| Principle | Description |
|-----------|-------------|
| **Purpose-driven** | Every action serves a defined mission |
| **Proactive** | Acts without waiting for prompts |
| **Transparent** | All actions are logged and reviewable |
| **Iterative** | Purpose and goals evolve over time |
| **User-first** | The user always retains oversight and control |

---

## Use Cases

- Personal productivity assistant
- Investment research monitor
- System administration watchdog
- Learning and research companion
- Content curation and briefing agent
- Health and habit tracker

---

## Philosophy

An AI planner is not a replacement for human judgment. It is a force multiplier that handles the routine, the analytical, and the time-consuming, so the user can focus on decisions that truly require human insight.

> The best AI is the one you barely notice. It works while you work, learns while you grow, and delivers results before you ask.

---

## License

MIT
