# CSL Lab Website — Project Memory

## Stack
- Jekyll 4.3, hosted on GitHub Pages at csl-lab-upenn.github.io
- Liquid templates, SCSS (auto-included from `_styles/`), custom Ruby plugins in `_plugins/`
- Collections: `_members/`, `_collabs/`, `_posts/`

## Key Architecture
- **Theme colors/fonts**: `_styles/-theme.scss` (CSS custom properties, auto-loaded at runtime)
- **All SCSS files** in `_styles/` are auto-included — no manual import needed
- **Google Fonts**: auto-generated from `--title`/`--heading`/`--body` vars in `-theme.scss` via `google_fonts` plugin
- **Team roles order**: `_data/member_roles.yaml` → consumed by loop in `team/index.md`
- **Member alumni**: add `group: alum` to member's front matter
- **Member files**: all kebab-case (e.g., `neil-sehgal.md`) — five renamed from PascalCase via `git mv`

## Design — Penn Engineering Aesthetic
- Primary: `#011F5B` (Penn navy), Secondary: `#3E7CB9` (medium blue)
- Fonts: Montserrat (headings), Inter (body), Roboto Mono (code)
- Rounded corners: 6px; subtle directional shadow

## Contact Page
- Address: Amy Gutmann Hall, 3317 Chestnut Street, Philadelphia, PA 19104
- Image: `images/AmyGuttmanHall.jpg` ✓ (present)
- Google Maps: https://share.google/M67KXUei9t0Yspc5P

## Custom Includes Added
- `_includes/team-collage.html` — dynamic CSS grid of active (non-alum) members
- `_styles/team-collage.scss` — collage grid styles
- `_styles/research-themes.scss` — themed research area cards on research page
- `_data/member_roles.yaml` — ordered role list for team page

## Cleaned Up (session 3)
- Deleted 7 unused images: LevineHall, team_collage, team_collage2, shreya_havaldar (dupe), member, photo, placeholder
- Fixed `_layouts/collab.html` (was almost entirely commented-out / broken)
- Simplified `_includes/portrait-collab.html` (removed duplicated logic from portrait.html)
- Removed dead commented code from `_layouts/post.html`, `_includes/post-info.html`
- Restored publication date display in blog posts (was commented out)
- Removed duplicate root-level keys from `_config.yaml`
