# carlosali.com

Personal site for Carlos Ali — Quote-to-Cash & CPQ thought leadership.

Built with [Astro](https://astro.build). Hosted on [Netlify](https://netlify.com).

## Quick Start

```bash
npm install
npm run dev        # Local dev server at localhost:4321
npm run build      # Build for production (outputs to /dist)
npm run preview    # Preview production build locally
```

## Adding Articles

Drop a `.md` file in `src/content/articles/` with this frontmatter:

```markdown
---
title: "Your Article Title"
description: "A one-line summary for cards and SEO."
date: 2026-03-01
tags: ["Salesforce CPQ", "Revenue Cloud"]
---

Your article content here...
```

## Deployment

### Option A: GitHub + Netlify (Recommended)

1. Push this repo to GitHub
2. Connect the repo to Netlify (netlify.com → New site from Git)
3. Netlify auto-detects Astro and deploys on every push
4. Add custom domain in Netlify → Domain settings → Add carlosali.com

### Option B: Manual Deploy

```bash
npm run build
# Upload the /dist folder to any static host
```

### GoDaddy DNS Setup

In GoDaddy DNS settings for carlosali.com:

1. Delete existing A records pointing to old hosting
2. Add CNAME: `www` → `your-site-name.netlify.app`
3. Add A record: `@` → Netlify load balancer IP (provided in Netlify dashboard)
4. Or use Netlify DNS entirely (recommended — transfer nameservers)

After DNS propagates (~15 min), Netlify auto-provisions SSL.

Then cancel your "Affordable Web Hosting" plan in GoDaddy.
