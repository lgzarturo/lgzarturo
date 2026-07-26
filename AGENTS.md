# AGENTS.md

## Repo Purpose

This is a **GitHub profile README** repository. No application code, no build system, no tests, no linting.

Contents:
- `README.md` — profile page rendered on github.com/lgzarturo
- `assets/` — static images referenced by README
- `.github/workflows/arthurolg-workflow.yml` — scheduled Action that auto-updates the blog section

## GitHub Action (blog-post-workflow)

`arthurolg-workflow.yml` pulls latest blog posts and injects them into `README.md` using comment tags:

- **Comment tag:** `BLOG-ALG` (`<!-- BLOG-ALG:START -->` / `<!-- BLOG-ALG:END -->`)
- **Feed:** `https://www.arthurolg.com/rss.xml` (the only working feed; `index.xml` returns 404 and `sitemap-0.xml` has no titles/dates)
- **Action pinned by SHA:** `gautamkrishnar/blog-post-workflow@2786e54a...` (release 1.9.6). Do NOT change back to `@master` — supply-chain risk.
- Trigger: hourly cron + `workflow_dispatch` (manual run from GitHub UI)

**Do not** remove or rename the HTML comment markers in `README.md` — the workflow depends on them to locate injection points. After editing README sections, verify the tags still exist.

## Profile conventions

- Language: **Spanish-first** (target audience is LatAm/hospitality clients), with English tech keywords (Spring Boot, SaaS, Technical Leader) for recruiter search.
- Do not add content claiming AI/ML products or metrics that don't exist — narrative must match visible repos.
