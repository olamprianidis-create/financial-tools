# CLAUDE.md — Financial Tools Project

## Project
Standalone HTML/CSS/JS financial calculators for public use.
Hosted on GitHub Pages. Each tool = one self-contained index.html.

## Folder Structure
tools/          → approved, live tools (one subfolder per tool)
outputs/        → staging area for new/edited tools awaiting review
design/         → design-system.md + template.html
shared/         → style.css, header.html, footer.html
skills/         → build-tool.md, style-guide.md, deploy-checklist.md

## Every Session: Read First
1. design/design-system.md
2. design/template.html
3. shared/style.css

## Task: Build New Tool
1. Read design files (above)
2. Ask clarifying questions — do NOT build until I answer
3. Start from design/template.html — never from scratch
4. Use shared/style.css — no inline styles, no external frameworks
5. Save to outputs/[tool-name]/index.html
6. Report: what you built, assumptions made, what to review
7. Wait for approval before moving to tools/

## Task: Edit Existing Tool
1. Read the existing file in tools/ first
2. Ask clarifying questions before making any changes
3. Make edits in place
4. Report exactly what changed and why

## Task: Fix a Bug
1. Read the file, identify the bug
2. State what you think the cause is before fixing
3. Fix it, report what changed

## Rules — Always
- Ask clarifying questions before every build, no exceptions
- One tool = one folder = one index.html
- Never overwrite tools/ directly — new tools go to outputs/ first
- Never use Bootstrap, Tailwind, or external CSS frameworks
- Never add features I didn't ask for
- All tools must be mobile responsive
- Verify math logic with 3 manual examples before saving
- No data collection, no external API calls unless I request

## Rules — Never
- Build without asking clarifying questions first
- Skip the template and start from scratch
- Write inline styles
- Push to GitHub — I handle all deployments
- Move files from outputs/ to tools/ without my approval

## Clarifying Questions To Ask For New Tools
- What inputs does the user provide?
- What does it calculate / output?
- Any specific formulas or logic to follow?
- Any edge cases to handle (e.g. zero values, negatives)?

## Deploy
I handle all GitHub pushes. Run skills/deploy-checklist.md
before telling me a tool is ready.
