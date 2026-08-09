# telegram-gmp-bot

Compact Railway deployment of the complete Telegram referral/agent bot.

The full original application is embedded in `app.py`, so the repository only
needs five top-level files. No bot features, admin pages, templates, services,
handlers, or static assets were intentionally removed.

## Railway
1. Deploy this repository.
2. Add a PostgreSQL service.
3. Set the variables from `.env.example`.
4. Set `DATABASE_URL` to Railway PostgreSQL's `DATABASE_URL`.
5. Start command: `python app.py`.

Never commit a real BOT_TOKEN or admin password.
