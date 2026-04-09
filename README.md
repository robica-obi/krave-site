# Krave — Landing Page

Static landing page for [Krave](https://krave.studio), a video editing agency for eCom brands, SaaS companies, personal brands & YouTubers.

## Stack

Plain HTML/CSS/JS — no build step, no dependencies, no framework. Single file deploys.

## Structure

```
krave-site/
├── index.html       # The entire site
└── README.md
```

## Deploy (Cloudflare Pages)

This repo is connected to Cloudflare Pages. Every push to `main` auto-deploys.

**To publish changes:**

```bash
git add .
git commit -m "your message"
git push
```

Cloudflare picks it up within ~30 seconds.

## Local Preview

Just open `index.html` in your browser. No server needed.

```bash
open index.html   # macOS
start index.html  # Windows
```

## Customization

All content lives in `index.html`. Search for these placeholders and replace them:

| Placeholder | Replace with |
|---|---|
| `hello@krave.studio` | Your real email |
| `$997`, `$1,997` | Your real pricing |
| `BRANDNAME`, `SHOPIFY CO` etc. | Real client names |
| Testimonial names/quotes | Real testimonials |
| `kree8.studio` booking link | Your Calendly or booking URL |
