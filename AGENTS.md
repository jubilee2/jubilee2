# AGENTS.md — Instructions for Codex (jubilee2.github.io)

## Project overview
This is a GitHub Pages + Jekyll personal website.
Primary goals:
- Clear professional homepage
- Projects portfolio (3–5 anchor projects)
- Optional blog posts
- Simple, low-maintenance structure

## Tech constraints
- Must be compatible with GitHub Pages’ Jekyll build.
- Prefer Markdown content and minimal plugins.
- Avoid adding dependencies that GitHub Pages won’t build by default.

## Content rules
- Do NOT include any sensitive or internal-only information (e.g., patient data, private details, internal URLs).
- If a project is not public, summarize at a high level and omit private links.
- Keep tone: professional, concise, technical.

## Site structure conventions
Preferred pages:
- index.md (Home)
- about.md
- projects.md
- cv.md
- contact.md

If adding project detail pages:
- Put them under `_projects/` as a Jekyll collection. This is the preferred method for consistency.

If adding blog posts:
- Put them under `_posts/` with `YYYY-MM-DD-title.md`.

## Style guidelines
- Keep layout clean and readable (minimal theme, accessible typography).
- No heavy animation.
- Avoid large images; optimize if added.
- Ensure navigation links work with baseurl.

## Jekyll configuration
- For user site: baseurl should be empty.
- Update `_config.yml` carefully; explain changes in PR/commit message.

## Testing
When making structural changes:
- Verify site builds (no Liquid/Jekyll errors).
- If you propose local testing steps, include them, but don’t require them.

## Review guidelines
- Prefer small, safe changes.
- Don’t change theme unless asked.
- Don’t add analytics or tracking unless asked.
