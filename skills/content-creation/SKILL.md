# Skill: Content Creation 🎬

## Purpose
Autonomous content pipeline for YouTube, TikTok, and Instagram.
Runs idea capture, weekly planning, script writing, and analytics.

## Activation Triggers
- "content", "video", "script", "post", "youtube", "tiktok", "instagram"
- "idea", "record", "publish", "analytics", "views"
- Evening cron (19:00 WAT) — YouTube scan
- Evening cron (20:00 WAT) — idea compilation
- Monday cron (08:00 WAT) — weekly plan
- Tuesday cron (09:00 WAT) — script writing
- Sunday cron (18:00 WAT) — analytics

## File Structure
- ideas/sources/youtube-ai-channels.md — channels to monitor
- ideas/sources/telegram-ideas.md — ideas from Telegram
- ideas/sources/twitter-ideas.md — ideas from Twitter
- ideas/logs/youtube-video-log.md — daily scan results
- ideas/combined-ideas.md — master ideas file
- content/weekly-plans/current-week.md — editorial calendar
- content/scripts/current-scripts.md — ready-to-record scripts
- analytics/raw/metrics-log.md — platform metrics
- analytics/dashboard/dashboard.html — visual dashboard

## Content Pillars
1. AI & n8n automation for African businesses
2. Building with Claude, OpenAI, LangChain, FastAPI
3. OpenClaw local AI agent setups
4. Current AI news and tool breakdowns
5. How to get best results from AI tools
6. Veloxa/VexaAI founder journey
7. ML & Data Science made practical

## Script Format
Hook → Context → Core Value → Proof/Demo → CTA
- TikTok/Instagram: 45-90 seconds
- YouTube: 5-10 minutes
