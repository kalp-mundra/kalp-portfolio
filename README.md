# Kalp Mundra — Personal Portfolio

A clean, interactive, single-page portfolio website built with pure HTML, CSS, and JavaScript. No frameworks, no build tools — just drop it in a repo and deploy.

🌐 **Live:** [(https://kalpmundra-portfolio.vercel.app/)]

---

## Preview

| Section | Highlights |
|---|---|
| Hero | Typing animation, animated badge, smooth scroll |
| About | Skill radar chart with scroll-triggered draw animation |
| Experience | Timeline with current role highlighted in green |
| Projects | Hover cards with tech tags |
| Skills | Grouped chips with hover states |
| Achievements | Award & activity cards |
| Resume | Download PDF + View Online buttons |
| Contact | All social links in one place |

---

## Repo structure

```
portfolio/
├── index.html               # Entire portfolio (single file)
└── Kalp_Mundra_Resume.pdf   # Resume — linked from the portfolio
```

---

## Tech used

- **HTML5 / CSS3 / Vanilla JS** — no frameworks or dependencies
- **Google Fonts** — Space Grotesk, Inter, JetBrains Mono
- **SVG animations** — hand-coded radar chart, scroll-triggered fade-ins
- **Deployed on Vercel** — auto-redeploys on every push to `main`

---

## Running locally

No build step needed. Just open `index.html` directly in your browser:

```bash
git clone https://github.com/YOUR_USERNAME/portfolio.git
cd portfolio
# open index.html in your browser
```

Or use VS Code's Live Server extension for hot reload.

---

## Deploying to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → import this repo
3. Leave all settings as default (no build command needed)
4. Click **Deploy** — live in ~30 seconds

Every subsequent `git push` to `main` triggers an automatic redeploy.

---

## Updating your resume

Replace `Kalp_Mundra_Resume.pdf` in the repo with your updated PDF (keep the same filename), then push. Vercel will redeploy automatically and the download link stays unchanged.

---

## Customisation

All content lives in `index.html`. Key things to update:

- **Links** — search for `YOUR_RESUME_LINK_HERE`, `https://linkedin.com`, `https://github.com` and replace with your real URLs
- **Projects** — find `<!-- PROJECTS -->` section and update GitHub/demo links
- **Radar chart** — edit the `axes` array in the `<script>` section to adjust skill values
- **Colors** — CSS variables are at the top of the `<style>` block under `:root`

---

## License

Feel free to fork and adapt for your own portfolio. A credit back is appreciated but not required.

---

*Built by [Kalp Mundra](mailto:mundrakalp030@gmail.com) · Jaipur, Rajasthan · 2026*
