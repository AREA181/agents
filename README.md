# AGENTS — Public GitHub Pages Package

**Public URL:** https://agents.3-2-1.ai/  
**Business and commissions:** https://3-2-1.ai/agency  
**Identity:** THE AGENCY — Universe System Architects (U.S.A.)  
**Credit:** MONKISM × IGMUS

## Scope
A standalone introductory fade and rotating quote experience. Visitors can optionally follow one link to the business site. The site does not process commissions, payments or sign-ins and has no third-party runtime dependencies.

The text files and JSON in this repository are a **public LLM information packet**, not a functioning AI-agent API or remotely executable tool specification. They can help crawlers and assistants describe and link to the official sites but do not ensure discovery, indexing or obedience by external systems.

## Publish with GitHub Pages
1. Upload the **contents of this folder** to the root of a public GitHub repository (not the private reference documents).
2. In repository settings, enable GitHub Pages deployment from the root of your chosen publishing branch.
3. Set the custom domain to `agents.3-2-1.ai` (the `CNAME` file is already present).
4. At the DNS provider for `3-2-1.ai`, create a **CNAME record** for host `agents` pointing to `<your-github-username>.github.io` (replace placeholder with your actual GitHub Pages owner; follow GitHub's current domain guidance).
5. Wait for DNS and Pages verification; enable **Enforce HTTPS** when available.
6. Check the public URL, fade, another-transmission button, Agency link, favicon, `/llms.txt`, `/llms-full.txt` and `/action-packet/manifest.json`.

Do not point the subdomain at the Agency site's host. The two properties must remain independent.

## Safe public-maintenance checklist
- Keep offers, commission prices, contracts, client forms and private documents on the Agency side only.
- Do not publish source design notes or confidential architecture in this repository.
- Keep the quote inventory in `index.html` if the site must remain a single self-contained page.
- `robots.txt` and the `llms` files are suggestions to indexing or AI tools, not access-control mechanisms.
- Any public GitHub repository is readable in full, including git history. Review commits before publishing.

## File guide
- `index.html`: complete static experience.
- `assets/favicon.svg`: independent icon.
- `CNAME`: custom-domain mapping.
- `llms.txt`, `llms-full.txt`: public machine-readable overview.
- `action-packet/`: public identity and navigation metadata.
- `AGENTS.md`: boundaries for future code-maintenance agents.
- `robots.txt`, `sitemap.xml`: crawler discovery metadata.

All quote text beyond the two established 3-2-1 phrases is proposed original site copy, for owner editorial approval. No real person is attributed invented quotations.
