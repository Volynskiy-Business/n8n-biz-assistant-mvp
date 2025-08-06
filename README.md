# n8n Business Assistant MVP

Production-ready automation stack for SMEs and individuals.
Stack: n8n, PostgreSQL, WhatsApp/Telegram bots, AI-assistant, Docker Compose.

## Features
- Lead collection from WhatsApp/Telegram/web
- Automated CRM with PostgreSQL
- 24/7 AI-assistant (multi-channel)
- Business email integration via Mailcow

## Getting Started

```bash
git clone git@github.com:Volynskiy-Business/n8n-biz-assistant-mvp.git
cd n8n-biz-assistant-mvp
cp .env.example .env
# Edit secrets in .env, then:
docker compose up -d
