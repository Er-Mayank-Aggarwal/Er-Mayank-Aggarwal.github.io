# Mayank Aggarwal — Portfolio

Personal portfolio website for **Mayank Aggarwal**, B.E. Computer Science student at MBM University, Jodhpur.

Built with static HTML/CSS — no build step. Hosted on GitHub Pages.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

- `index.html` — single-page site: hero, areas of interest, projects, experience, education, skills, achievements & leadership, about, contact
- `assets/style.css` — design system (Inter / JetBrains Mono, red accent)
- `assets/Mayank-Aggarwal-CV.pdf` — downloadable CV

## Updating

- Content lives inline in `index.html` sections; add new projects under "Projects" and new experience under "Experience".
- Replace `assets/Mayank-Aggarwal-CV.pdf` to update the CV.
- Deploy: `git add -A && git commit -m "..." && git push` (GitHub Actions workflow in `.github/workflows/pages.yml` deploys the site).
