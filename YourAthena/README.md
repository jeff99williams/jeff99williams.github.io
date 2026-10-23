# YourAthena landing page

Static GitHub Pages page at `https://yourcio.ca/YourAthena/`. The public `https://yourathena.ai/` currently redirects here.

## Preview

From the repository root:

```sh
python -m http.server 8876 --bind 127.0.0.1
```

Open `http://127.0.0.1:8876/YourAthena/`. No application server, API keys or build step is required. The page uses native anchor links and expandable details; contact actions open an email draft. No question is sent to an AI service.

## Source and assets

- This page is maintained in `jeff99williams/jeff99williams.github.io`, on `main` under `YourAthena/`.
- The design and consulting copy reference is `jeff99williams/VirtualConsultant`, branch `main`, `docs/index.html` (not its default `VC3` branch). That source matched the public `https://yourcio.ca/VirtualConsultant/` page when checked on 2026-10-23.
- Athena logos, favicons and the sample memo were copied from that public page's `assets/` directory. They are stored locally here so the landing page does not depend on cross-repository asset paths.
- The case figures describe published house cases based on public information and synthetic operating records. Preserve that disclosure when editing them.
- Newsreader and Public Sans are loaded from Google Fonts, with system-font fallbacks.
- Keep `assets/athena.css` and `index.html` together. Preserve relative asset URLs so this page works under its `/YourAthena/` subdirectory.

## Release boundary

The Answers + advice proposal is prepared on `codex/athena-answers-advice`. Review the preview before merging: the site's Pages publishing source is `main`, so merging is the release step. The current proposal does not change the root YourCIO page, domain routing, the VirtualConsultant application, or the old Azure golf demo.
