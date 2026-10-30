# SoundWave site — Handoff

## Current state
Static landing page + privacy + terms (index.html, privacy.html, terms.html, style.css) on GitHub Pages
(repo benshafne3r/soundwave-site), custom domain soundwaveprojects.com (CNAME file). Contact b@soundwaveprojects.com.

## In progress
GoDaddy DNS switched 2026-10-30 (A @ -> 185.199.108-111.153, www CNAME -> benshafne3r.github.io; Microsoft 365 email records untouched).
Waiting on propagation + GitHub HTTPS certificate, then enforce HTTPS:
`gh api -X PUT repos/benshafne3r/soundwave-site/pages -F https_enforced=true`

## Next steps
1. Confirm DNS + enforce HTTPS in repo Settings → Pages.
2. Use soundwaveprojects.com/privacy.html and /terms.html in TikTok app review.

## Key decisions
- Plain static HTML, no build. Privacy/terms written for read-only TikTok analytics (Post for Me).

## Gotchas / setup
- Push to main = deploy. Edit HTML directly.

## Open questions
- None.
