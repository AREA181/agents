# AGENTS — Business Universe Quote Calculator

**This is the actual pricing quote calculator, not an inspirational quote generator.**

- `index.html`: fully functional calculator including intro fade, prices, comparisons, print and JSON download.
- `CNAME`: existing custom domain, agents.3-2-1.ai.
- `AGENTS.md`, `llms.txt`, `llms-full.txt`, `action-packet.json`: public LLM information packet.
- `.nojekyll`, `robots.txt`, `sitemap.xml`: static publishing metadata.

## GitHub Pages release
Upload the *unzipped contents* to the repository root, overwriting matching filenames. On GitHub Pages, deploy branch `main`, folder `/ (root)`. Your custom domain is already configured; do not change DNS for an HTML update.

GitHub's website uploader does not unzip ZIPs automatically. Select all extracted files and upload them together, or replace `index.html` alone to repair the deployed experience; the estimator is fully self-contained in that one file.

## User privacy
Browser-only price calculations. No submission, database, payment or API calls. Inquiries go to https://3-2-1.ai/agency.

## Four visual skins
Select **Default**, **Bullish**, **Peak Sun**, or **BBQ Mode** in the homepage top bar. Each changes colors without resetting or modifying calculator selections. The selected skin is remembered in the visitor's browser when browser storage is available. No external assets or API calls are required.

**To update GitHub Pages:** upload the contents of this extracted folder together to your existing `AREA181/agents` repository on `main` at the root; replace matching files. Or replace just `index.html` to add the skins immediately. Your GitHub Pages and custom-domain settings need no changes.
