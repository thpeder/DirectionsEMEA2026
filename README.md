# Directions EMEA 2026 — Building Agents in Business Central

Workshop site for the *Building Agents in Business Central* session at Directions EMEA 2026.

## 🌐 Workshop Site

**[https://thpeder.github.io/DirectionsEMEA2026/](https://thpeder.github.io/DirectionsEMEA2026/)**

## Workshop Stages

| Stage | Title |
|-------|-------|
| 1 | Introduction & Setup |
| 2 | Your First Agent |
| 3 | Customizing the Agent's Profile |
| 4 | Inspecting Task Logs |
| 5 | Make It Your Own |
| 6 | Export & Import |
| 7 | Agent in AL |
| 8 | Customizing the Setup Page |
| 9 | Programmatic Tasks |
| 10 | Bring Your Own App |

## Local Development

The site uses [Jekyll](https://jekyllrb.com/) (GitHub Pages' built-in static site generator).

```bash
# Install dependencies
gem install bundler jekyll

# Serve locally
jekyll serve
# → http://localhost:4000/DirectionsEMEA2026/
```

## Repository Structure

```
_config.yml          # Site configuration and stage definitions
_layouts/
  default.html       # Base layout (topbar + sidebar)
  stage.html         # Stage layout (adds progress bar + prev/next nav)
assets/css/
  style.css          # Site styles
index.md             # Workshop overview / landing page
stages/
  01-introduction.md
  02-first-agent.md
  03-profile-customization.md
  04-testing.md
  05-publishing.md
  06-export-import.md
  07-al-agent.md
  08-setup-page.md
  09-programmatic-tasks.md
  10-bring-your-own-app.md
```
