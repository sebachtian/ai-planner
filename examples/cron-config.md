# Cron Schedule Examples

## Hermes Cron Syntax

```bash
# Every 6 hours
hermes cron create \
  --schedule "0 */6 * * *" \
  --prompt "Check PURPOSE.md, evaluate progress against PLAN.md, execute next action, and report back." \
  --deliver origin
```

## With Skills

```bash
# Scheduled with AI Planner skills
hermes cron create \
  --name "ai-planner-checkin" \
  --schedule "0 */6 * * *" \
  --skills ai-planner \
  --prompt "Execute your scheduled check-in per the AI Planner framework."
```

## Cron Script Pattern

```bash
#!/bin/bash
# /home/user/.hermes/scripts/ai-planner-checkin.sh
# This script runs on every cron tick

cat << 'EOF' | hermes
I am running my scheduled check-in. Read PURPOSE.md, PLAN.md, and GOALS.md 
from the ai-planner repository. Evaluate what has been done, determine the 
next actionable step, execute it, and summarise the results.
EOF
```

## Common Schedules

| Schedule | Cron Expression |
|----------|----------------|
| Every 6 hours | `0 */6 * * *` |
| Every 12 hours | `0 */12 * * *` |
| Daily at 7 AM | `0 7 * * *` |
| Daily at 6 PM | `0 18 * * *` |
| Every Monday 9 AM | `0 9 * * 1` |
| Every hour | `0 * * * *` |
| Every 30 minutes | `*/30 * * * *` |
