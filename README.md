# 🤖 Telegram Bot Starter Kit
A complete, modular starter ecosystem for building and deploying Telegram bots using Java, Spring Boot, Docker, and GitHub Actions.

---

## 🧱 Repositories

| Name | Description|
|------|------|
|[telegram-bot-template](https://github.com/DmitriyLadutsko/telegram-bot-template)|A clean, production-ready Spring Boot Telegram bot with CI/CD, Docker, and automated releases|
|[telegram-bot-server-infra](https://github.com/DmitriyLadutsko/telegram-bot-server-infra)|Infrastructure project for deploying bots on a VPS with Docker, Nginx, and GitHub Webhook auto-deploy|

---

## 📦 What's Included

- ✅ Production-ready codebase for Telegram bots
- 🐳 Infrastructure setup for VPS deployment
- 🔁 CI/CD with GitHub Actions and Docker Hub
- 🔔 GitHub Webhooks triggering auto-deploys
- 🧰 Local Makefile-based automation
- 🔐 HTTPS with Let's Encrypt + Nginx
- 🧾 VERSION and changelog generation
- 📄 This hub project to unify it all

---

## 🚀 Getting Started
1. Use the bot template
```bash
git clone https://github.com/DmitriyLadutsko/telegram-bot-template my-bot
cd my-bot
make run-local
```
2. Deploy using the infra
```bash
curl -sSL https://raw.githubusercontent.com/DmitriyLadutsko/telegram-bot-server-infra/main/bootstrap.sh | bash
```
- Clone the infra repo into `/home/deploy/app`
- Fill in `.env` with secrets
- Run `docker compose up -d`

Your bot is now deployed and auto-updatable! ✅

---

## 📚 Documentation
- [telegram-bot-template README](https://github.com/DmitriyLadutsko/telegram-bot-template/blob/main/README.md)
- [telegram-bot-server-infra README](https://github.com/DmitriyLadutsko/telegram-bot-server-infra/blob/main/README.md)

---

## 🌍 GitHub Pages (coming soon)
We plan to launch a minimal website with:
- 🌐 Landing page
- 📖 Quickstart guide
- 🗺️ Project roadmap
- 🧩 Add-your-own-bot examples

---

## ✅ Use Cases
- Personal bots with CI/CD
- Family utility bots
- Internal tools & alerts
- Telegram AI or assistants

---

## 🧠 Built With
- Java 17 + Spring Boot
- TelegramBots Java SDK
- Docker & Docker Compose
- GitHub Actions
- Make

---

## 📌 Contributing
This is a personal ecosystem, but feel free to fork or suggest ideas via [Issues](https://github.com/DmitriyLadutsko/telegram-bot-starter-kit/issues) 🚀

---

🎉 Happy hacking!
By @DmitriyLadutsko
