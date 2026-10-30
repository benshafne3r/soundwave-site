# SoundWave site — Handoff

## Current state
Static landing page + privacy + terms (index.html, privacy.html, terms.html, style.css) on GitHub Pages
(repo benshafne3r/soundwave-site), custom domain soundwaveprojects.com (CNAME file). Contact b@soundwaveprojects.com.

## In progress
Nothing. Live at https://soundwaveprojects.com with HTTPS enforced (cert approved 2026-10-30).

## Next steps
1. Use https://soundwaveprojects.com/privacy.html and /terms.html in TikTok app review.

## Key decisions
- Plain static HTML, no build. Privacy/terms written for read-only TikTok analytics (Post for Me).

## Gotchas / setup
- Push to main = deploy. Edit HTML directly.
- If HTTPS cert ever stalls: remove + re-add custom domain in repo Settings → Pages (only after DNS points to GitHub).
- GoDaddy DNS: A @ → 185.199.108-111.153, www CNAME → benshafne3r.github.io. Microsoft 365 email records must stay.

## Open questions
- None.
