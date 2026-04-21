# gexplo-model-landing

Landing page for **model.gexplo** — subsurface modeling services.

Static HTML + Tailwind (CDN) + vanilla JS. Deployed on Vercel at https://model.gexplo.com.

## Stack
- Static HTML (no build step)
- Tailwind via CDN
- Google Fonts: Inter + JetBrains Mono
- Supabase JS client (CDN) for lead capture

## Local preview
```
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy
Auto-deploys on push to `main` via Vercel.
