# EcoLearn — Smart Sustainability Learning Platform

A polished, responsive React + TypeScript hackathon MVP that helps students learn about sustainability, build practical habits, and explore their connection to the UN Sustainable Development Goals.

## Included features
- Student dashboard with progress, points, badges, daily challenge and weekly activity chart
- Six short sustainability lessons with actionable takeaways
- Five-question interactive knowledge quiz with scoring and explanations
- Transparent rule-based lesson recommendations (no AI API is claimed)
- Six daily eco-challenges with points and duplicate-reward prevention per challenge per day
- Environmental impact estimates with visible assumptions and disclaimers
- SDG explorer for goals 4, 6, 7, 12, 13, 14 and 15
- Educator analytics and a leaderboard clearly labelled as fictional demo data
- Responsive desktop/mobile navigation and localStorage progress persistence

## Run locally
1. Install Node.js 20 or newer.
2. Clone this repository and enter the project folder:
   `git clone https://github.com/ssachit2009/eco-vision.git`
   `cd eco-vision`
3. Install dependencies: `npm install`
4. Start development server: `npm run dev`
5. Open the local URL shown by Vite.

Create a production build with `npm run build`; preview it using `npm run preview`.

## Publish with GitHub Pages
A GitHub Actions workflow is included at `.github/workflows/deploy.yml`.
1. Open **Settings → Pages** in this repository.
2. Set the Pages source to **GitHub Actions**.
3. Open **Actions** and check the deployment workflow. It runs on pushes to `main`.
4. After a successful run, open: https://ssachit2009.github.io/eco-vision/

The first deployment may take a few minutes. If the workflow has not run yet, the Pages link may not be live until the workflow succeeds.

## Honest demo-data notes
- Progress is saved in the current browser's localStorage. It is not synced across devices and is not a real multi-user account.
- Analytics and leaderboard profiles are fictional examples for demonstration, not verified college results.
- Impact values are estimates using simple illustrative per-action assumptions, not independently verified environmental outcomes.
- Personalization is rule-based. There is no live AI API or backend database connected.

## Stack
React, TypeScript, Vite, Recharts, Lucide React, CSS and browser localStorage.
