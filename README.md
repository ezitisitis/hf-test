# Gonka × Hyperfusion — Official Landing Page

Trilingual (EN/ZH/RU) landing page for Hyperfusion's Gonka mining infrastructure service.

## Deploy on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. Your site will be live at `https://<username>.github.io/<repo-name>/`

### Custom domain (optional)

To use a custom domain, add your domain to the `CNAME` file and configure DNS.

## Stack

- Single-file React app (no build step)
- React 18 via CDN
- Zero dependencies beyond React/ReactDOM

## LLM / AI Agent Optimisation

These files were generated to make the single-page site (https://hyperfusion.io/) easier for LLMs and AI agents to discover and read.

### Files
- `index.content.json` — machine-readable extraction of key content from `index.html`
- `.well-known/ai-plugin.json` — discovery manifest pointing to the HTML page and `index.content.json`
- `robots.txt` — allows crawling and points to the sitemap
- `sitemap.xml` — sitemap pointing (only) to `https://hyperfusion.io/`
- `llms.txt` — quick pointers to the above resources

### Deployment
Place these files in your website root so they resolve as:
- `https://hyperfusion.io/<file>`