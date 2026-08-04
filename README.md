# pbuilder

How the best product builders use Pendo.

A collection of Claude skills for every stage of the product cycle — monitoring, discovery, validation, experimentation, launch, and measurement. Each skill is a slash command backed by live Pendo data.

Works with Claude Code and Cowork.

---

## Install

```bash
git clone https://github.com/pendo-io/pbuilder.git ~/.claude/skills/pbuilder
```

Then authenticate Pendo once:

```
/mcp
```

That's it.

---

## Skills

### Monitor
Keep a constant pulse on what's happening.

| Skill | What it does |
|---|---|
| [`pulse`](./pulse/) | Weekly product health digest — usage trends, feedback themes, guide performance |
| [`bug-radar`](./bug-radar/) | Daily scan for emerging bugs and errors before your users report them |
| [`usage-watch`](./usage-watch/) | Daily usage checker — flag drops, spikes, and anomalies in key features |

### Uncover
Find the real problems worth solving.

| Skill | What it does |
|---|---|
| [`theme-scan`](./theme-scan/) | Thematic analysis of recent feedback — cluster signals into actionable themes |
| [`ticket-dig`](./ticket-dig/) | Root cause analysis for a support ticket using session replays and devlogs |
| [`blast-radius`](./blast-radius/) | How many users are affected by a known issue |
| [`friction-map`](./friction-map/) | Blends rage clicks, drop-off, and qual feedback to surface where users are stuck |

### Validate
Build confidence before you commit.

| Skill | What it does |
|---|---|
| [`rice-score`](./rice-score/) | RICE scoring grounded in real Pendo data — reach and impact pulled automatically |
| [`idea-rank`](./idea-rank/) | Prioritise roadmap ideas by vote volume and customer segment |
| [`discovery-invite`](./discovery-invite/) | Create a Pendo guide that recruits users for discovery interviews |

### Experiment

| Skill | What it does |
|---|---|
| [`fake-door`](./fake-door/) | Set up a fake door test — guide, click tracking, and results in one command |

### Tag

| Skill | What it does |
|---|---|
| [`tag-new-feature`](./tag-new-feature/) | Tag a new feature in Pendo so everything else can measure it |

### Launch
Ship with confidence, nothing missed.

| Skill | What it does |
|---|---|
| [`launch-checklist`](./launch-checklist/) | End-to-end launch: feature flag, guide, sentiment survey, adoption goal, dashboard |

### Measure
Know if it landed.

| Skill | What it does |
|---|---|
| [`launch-watch`](./launch-watch/) | Weekly launch health update — adoption curve, guide engagement, NPS movement |
| [`bug-watch`](./bug-watch/) | Daily post-launch issue monitor — errors, regressions, support ticket spikes |
| [`exec-brief`](./exec-brief/) | Exec-ready summary of a launch or feature — one paragraph, the numbers that matter |

---

## How it works

Each skill is a folder with a `SKILL.md` file. Claude reads it as a slash command and calls the Pendo MCP for live data. No hardcoded queries, no stale exports — everything runs against your subscription in real time.

---

## Contributing

Built a skill that belongs here? Open a PR. The bar is: does it make product builders faster?

---

MIT License · [pendo-io](https://github.com/pendo-io)
