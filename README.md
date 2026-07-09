# 🎨 AI Image Generator + Telegram Bot (n8n)

Automated workflow that generates 4 AI images daily and posts 
them to a Telegram channel using n8n automation.

## 🔧 Tech Stack
- **n8n** — workflow automation (self-hosted)
- **Pollinations.ai** — free AI image generation
- **Telegram Bot API** — image delivery

## 🔄 Workflow
1. Schedule Trigger fires daily
2. Code node generates 4 image prompts
3. HTTP Request fetches AI images from Pollinations.ai
4. Telegram node posts each image to channel

## 🚀 How to Use
1. Install n8n: `npx n8n`
2. Import `workflow.json` via Settings → Import
3. Add your Telegram bot token as credential
4. Update Chat ID with your channel ID
5. Toggle workflow Active

## ⚙️ Setup Requirements
- Node.js installed
- Telegram Bot (create via @BotFather)
- Telegram Channel with bot as admin
