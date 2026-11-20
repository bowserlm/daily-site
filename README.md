# daily-site

DAILY's public home page and privacy policy, served by GitHub Pages (from the `release` branch) at
https://bowserlm.github.io/daily-site/ -- the links on DAILY's Google OAuth consent screen
(Branding: home page + privacy policy). Plain static files, no build step.

The app itself lives in the private repo `daily` (PERSONAL/DAILY).

Shipping: commit to main, look at both pages and sign (`~/.claude/hooks/look_gate.py --sign`), then
`git push origin main:release`. A push to main alone publishes nothing (the background sync pushes main).
