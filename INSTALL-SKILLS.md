# How to Install Skills on Another Bot

## Quick Install (2 steps)

### Step 1: Download and extract

Place the `cherub-skills.zip` file on your other Mac mini, then run:

```bash
cd ~/your-bot-workspace
unzip cherub-skills.zip
```

This creates a `skills/` folder with all 28 custom skills inside your bot's workspace.

### Step 2: Restart the bot

```bash
openclaw gateway restart
```

That's it! The bot will automatically detect the skills folder and load all skills.

---

## What's Included (28 skills)

### Marketing & SEO
- **marketing-mode** — 23 combined marketing skills (master skill)
- **marketing-skills** — Individual marketing sub-skills (CRO, ads, email, SEO, etc.)
- **seo-optimizer** — SEO audits, meta tags, schema, sitemaps
- **geo-optimization** — AI search visibility (ChatGPT, Perplexity, Google AI)

### Content Creation
- **create-content** — Transform ideas into platform-optimized content
- **content-writing-thought-leadership** — B2B content writing workflows
- **critical-article-writer** — Analytical articles with sharp voice
- **humanize** — Remove AI writing patterns from text
- **copywriting** (inside marketing-skills)

### Photography Marketing
- **pregnancy-photography-marketing** — Maternity photography marketing
- **family-photography-marketing** — Family photography marketing
- **birthday-photography-marketing** — Birthday photography marketing
- **first-birthday-photography-marketing** — First birthday photography
- **graduation-photography-marketing** — Graduation photography
- **business-photography-marketing** — Business photography

### Social Media
- **instagram** — Instagram integration
- **instagram-marketing** — Instagram marketing from product URLs
- **pinterest** — Pinterest API integration
- **pinterest-pub** — Pinterest publishing
- **social-media-management** — Social media management

### Web Development
- **frontend-design-ultimate** — Production-grade sites (React, Tailwind)
- **web-deploy-github** — Deploy to GitHub Pages
- **web-design-guidelines** — UI review for best practices
- **accessibility** — WCAG 2.1 AA compliance
- **landing-gen** — Generate landing pages
- **wordpress-publisher** — Publish to WordPress via API

### Other
- **ai-landing** — AI landing pages

---

## Folder Structure

```
your-bot-workspace/
├── AGENTS.md
├── SOUL.md
├── skills/           ← extracted here
│   ├── marketing-mode/
│   ├── marketing-skills/
│   │   └── references/
│   │       ├── ab-test-setup/
│   │       ├── analytics-tracking/
│   │       ├── copywriting/
│   │       ├── email-sequence/
│   │       ├── page-cro/
│   │       ├── paid-ads/
│   │       ├── seo-audit/
│   │       └── ... (23 sub-skills)
│   ├── seo-optimizer/
│   ├── pregnancy-photography-marketing/
│   └── ... (28 skill folders total)
```

## Verify Installation

After restarting, ask the bot:
> "List your available skills"

It should show all 28+ custom skills.
