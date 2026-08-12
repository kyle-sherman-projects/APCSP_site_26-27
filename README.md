# a site for my AP CSP class that weaves daily lessons between CodeHS & AP Classroom
# to access the site: https://kyle-sherman-projects.github.io/APCSP_site_26-27/

## Editing published lessons

Lesson pages under `docs/` include hand-authored Spanish translations of the
learning objectives that don't exist anywhere else as source text — the
generator in the main planning repo (`scripts/build_google_site.py`) can't
reproduce them. To change an existing lesson, edit that lesson's HTML file
directly. The generator is for scaffolding brand-new lesson/unit pages only.

All lesson pages share a single exit-ticket Google Form (not one per lesson)
— the embed URL is `EXIT_TICKET_FORM_URL` in `scripts/render_lesson_plans.py`.
