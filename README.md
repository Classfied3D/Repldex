[![Run on Replit](https://replit.com/badge/github/repldex/Repldex)](https://replit/com/github/repldex/Repldex)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Frepldex%2FRepldex)

# ⚠️ Repldex 3 is still under heavy development. ⚠️

# Repldex

Repldex is the unofficial community-editable encyclopedia of user created entries for the [Replit Discord Server](https://replit.com/discord). This repository contains the entire source code for both the website and the slash command Discord bot. Repldex uses [Svelte](https://svelte.dev/) and is hosted serverlessly on [Vercel](https://vercel.app/).

# Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

# Classfied Stuff

edit routes/login.ts to the repl url

edit the discord application to a redirect to repl-url/login

Env vars:
JWT_SECRET: generate via require('crypto').randomBytes(64).toString('hex')
MONGODB_URI: mongodb+srv://user:pass@name.mongodb.net
DISCORD_CLIENT_SECRET and DISCORD_CLIENT_ID, make a new discord application, add repl-url/login as a redirect and get the ID and secret (do all this from the oath2 2 tab of the discord dev console)