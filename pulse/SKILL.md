# pulse

Weekly product health digest. Run every Monday morning to know what changed, what spiked, and what needs attention before the week starts.

## When to use

- Weekly ritual before planning or standup
- Quick pulse check after a quiet period
- Before a leadership meeting

## What it does

1. Pulls feature and page usage trends for the past 7 days vs. the prior 7 days
2. Surfaces the top feedback themes from Pendo Listen
3. Checks guide performance — which guides are being dismissed, which are driving action
4. Flags any PES or NPS movement
5. Outputs a digest: what's up, what's down, what needs a closer look

## Usage

```
/pulse
```

Optional: scope to a specific app or segment

```
/pulse <app-name>
/pulse segment:<segment-name>
```

## Output

A short digest you can paste into Slack or read before your first meeting. No dashboard required.
