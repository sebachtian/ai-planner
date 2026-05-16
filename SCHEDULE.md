# Schedule Configuration

## Check-in Intervals

| Interval | Use Case | Example |
|----------|----------|---------|
| Every 6 hours | General purpose monitoring | `0 */6 * * *` |
| Daily (morning) | Daily briefing | `0 7 * * *` |
| Daily (evening) | End-of-day summary | `0 18 * * *` |
| Weekly | Planning and review | `0 9 * * 1` |

## Current Schedule

*Not yet configured. See examples/cron-config.md for setup instructions.*

## Delivery Channels

| Channel | Purpose |
|---------|---------|
| Discord | Primary communication (DM or channel) |
| Email | Formal reports and summaries |
| Local | File-based output for review |

## Configuration Template

```yaml
# ~/.hermes/config.yaml or environment-specific
cron:
  schedule: "0 */6 * * *"
  prompt: "Check PURPOSE.md, evaluate progress, and take next action."
  deliver: origin
```
