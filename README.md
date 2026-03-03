# ProofButton — The Accountability Button

**Battery-free. Wire-free. Excuse-free.**

A self-powered wireless button you stick anywhere to hold your family accountable, call for help, and automate your home — no batteries, no wiring, ever.

## Site Structure

```
public/          → Production website (Cloudflare Pages serves this)
  index.html     → Landing page (proofbutton.com)
  thank-you.html → Post-signup page
  assets/        → Images, icons, fonts

campaign/        → Campaign materials (not served publicly)
  campaign-page/ → Kickstarter copy, tiers, FAQ, stretch goals
  email-sequences/ → 7-email pre-launch drip sequence
  video/         → Script, Sora prompts, storyboard
  ads/           → Meta ad concepts + audience targeting
  press/         → Press release, media list, press kit
  social/        → Launch calendar, post templates, Reddit posts
  operations/    → Launch playbook, timeline, fulfillment plan
  competitive/   → Feature matrix, Flic & SmartThings comparisons
```

## Deployment

- **Production**: `main` branch → proofbutton.com (Cloudflare Pages)
- **Dev/Staging**: `dev` branch → dev.proofbutton.com (Cloudflare Pages preview)

## Tech Stack

- Static HTML + Tailwind CSS (via CDN)
- Cloudflare Pages hosting
- Email capture → Mailchimp/ConvertKit (swap form endpoint)

## Quick Start

1. Clone the repo
2. Open `public/index.html` in browser
3. Edit and push — Cloudflare auto-deploys

---

*Launching on Kickstarter — [proofbutton.com](https://proofbutton.com)*
