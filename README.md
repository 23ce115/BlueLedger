# BlueLedger 

A personal finance dashboard — encrypted, PIN-locked, and fully private.

## Features
- AES-256 encrypted localStorage — data is unreadable without your PIN
- PIN lock screen with auto-lock after 5 minutes
- Up to 4 cards, each with separate transactions and budgets
- Income & expense tracking with categories, recurring transactions, and budget limits
- Monthly summary reports and CSV export

## Security
- Your data never leaves your device — no backend, no database
- Only the last 4 digits of your card number are stored
- Forgetting your PIN means your data cannot be recovered (by design)

## Deploy to Vercel
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. Leave all settings as default — Vercel auto-detects static sites
4. Click Deploy

## Local Development
Just open `index.html` in a browser served via a local server:
```bash
npx serve .
```
Then visit `http://localhost:3000`

> **Note:** Each user's data is stored in their own browser's localStorage. 
> Clearing browser data or switching devices will lose data unless exported first.
