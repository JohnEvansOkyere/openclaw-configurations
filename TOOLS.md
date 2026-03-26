# TOOLS.md - John's Setup & Environment

## Machine
- **Host:** grejoy-laptop (Linux Ubuntu, x64)
- **Workspace:** /home/grejoy/.openclaw/workspace
- **Gateway:** ws://127.0.0.1:18789 (local loopback)
- **Dashboard:** http://127.0.0.1:18789/

## AI Model
- **Primary:** ollama/minimax-m2.7:cloud (205k context)
- **Ollama URL:** http://127.0.0.1:11434
- **Memory:** nomic-embed-text (semantic search)

## Content Pipeline Files
- **YouTube channels to monitor:** ideas/sources/youtube-ai-channels.md
- **Telegram ideas input:** ideas/sources/telegram-ideas.md
- **Twitter ideas input:** ideas/sources/twitter-ideas.md
- **YouTube scan log:** ideas/logs/youtube-video-log.md
- **Telegram processed log:** ideas/logs/telegram-log.md
- **Twitter processed log:** ideas/logs/twitter-log.md
- **Master ideas file:** ideas/combined-ideas.md
- **Weekly plan:** content/weekly-plans/current-week.md
- **Scripts:** content/scripts/current-scripts.md
- **Published archive:** content/published/
- **Raw analytics:** analytics/raw/metrics-log.md
- **Analytics dashboard:** analytics/dashboard/dashboard.html

## Cron Schedule (Africa/Accra timezone, UTC+0)
- **19:00 daily** → Evening YouTube Scan
- **20:00 daily** → Daily Idea Compiler
- **08:00 Monday** → Weekly Content Plan
- **09:00 Tuesday** → Weekly Script Writer
- **18:00 Sunday** → Weekly Analytics Fetch

## Channels
- **Telegram:** connected (primary idea capture channel)
- **Twitter/X:** not yet connected (ideas manually logged to twitter-ideas.md)
- **YouTube API:** not yet configured (needed for auto-posting + analytics)
- **TikTok API:** not yet configured (needed for auto-posting + analytics)
- **Instagram API:** not yet configured (needed for auto-posting + analytics)

## Content Platforms
- **YouTube:** 2 videos/week (educational, build-focused, 5-10 min)
- **TikTok:** daily (short punchy, 45-90 sec)
- **Instagram:** daily (visual/practical, 45-90 sec)

## Web Search
- **Plugin:** openclaw-web-search (@ollama/openclaw-web-search)
- **Status:** installed, enabled

## John's Contact
- **Email:** johnevansokyere@gmail.com
- **Phone:** +233 544 954 643
- **Location:** Accra, Ghana
- **GitHub:** https://github.com/JohnEvansOkyere
- **Portfolio:** https://personal-portfolio-website-beta-nine.vercel.app/
- **Company:** Veloxa Technology Ltd / VexaAI

## Pending Setup
1. Telegram bot token + pairing
2. YouTube Data API credentials
3. TikTok developer account
4. Instagram Graph API (Meta Business)
5. Streamlit analytics dashboard (dashboard.py)
