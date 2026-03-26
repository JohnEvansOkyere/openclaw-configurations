# Heartbeat Checklist

Run this check every 30 minutes during active hours.

## Check These Every Run

- Is there anything new in ideas/sources/telegram-ideas.md that hasn't been processed yet?
- Is there anything new in ideas/sources/twitter-ideas.md that hasn't been processed yet?
- Are any scripts in content/scripts/current-scripts.md overdue (older than 3 days)?
- Is the current week's plan missing? Check content/weekly-plans/current-week.md
- Any urgent messages from John via Telegram?

## Time-Based Checks

- Is it after 19:00 WAT (West Africa Time / UTC+0)? → Has the Evening YouTube Scan cron run today? Check ideas/logs/youtube-video-log.md for today's date
- Is it after 20:00 WAT? → Has the Daily Idea Compiler run? Check ideas/combined-ideas.md for today's entries
- Is it Monday? → Has the Weekly Content Plan been created? Check content/weekly-plans/current-week.md
- Is it Tuesday? → Have this week's scripts been written? Check content/scripts/current-scripts.md

## If Nothing Needs Attention

Reply: HEARTBEAT_OK
