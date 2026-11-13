# DuitPlan — Money Planner

A mobile-first, offline-first personal finance planner built as a static Progressive Web App.

## Features
- Dashboard with balance, monthly income, expenses, spending categories and recent transactions.
- Manual income and expense tracking with categories, dates, notes, search and filters.
- Monthly category budgets with progress indicators.
- Debt accounts with balance, monthly payment, due day, interest rate and payment recording.
- Savings goals with targets, target dates and contribution tracking.
- Monthly reports and savings-rate calculation.
- Currency preferences: MYR, USD, SGD, IDR, GBP and EUR.
- JSON export/import backup.
- Installable PWA with an offline service worker.

## Privacy and limitations
All records are stored in browser localStorage on the current device. There is no bank connection, cloud sync, account system or server-side database. Export backups regularly. Clearing browser/site data may erase records. DuitPlan is a tracking tool, not financial advice.

## Deploy to GitHub Pages
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. Pushes to `main` will run the deployment workflow.
4. When deployment succeeds, open the Pages URL and use your browser's **Add to Home screen** option.

The app is served from the repository root; no Cloudflare Worker or paid backend is required.
