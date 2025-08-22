# Submission Package — Assignment 3

## What to Submit
1. **Hosted website link (GitHub Pages)** — multi‑page portfolio built with Quarto.  
   - URL: https://<your-username>.github.io/<repo-name>/
2. **Single‑page portfolio link** (from Assignment 1) — paste your URL:  
   - URL: https://<your-username>.github.io/<single-page-repo>/
3. **Reflection** — already included as `reflection.qmd`. Export to PDF if required by your LMS.
4. **Appendix (LLM output, annotated)** — already included as `appendix.qmd` with LLM disclosure and revision notes.

## How to Host on GitHub Pages (Quarto)
```bash
# Inside the project folder
quarto preview  # optional local check

git init
git add .
git commit -m "Assignment 3: MBA portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main

# Publish to GitHub Pages
quarto publish gh-pages
```
GitHub Pages URL will look like: `https://<your-username>.github.io/<repo-name>/`

## Checklist (Accessibility & Usability)
- [ ] All navbar links work
- [ ] Resume downloads correctly
- [ ] Links have descriptive text (e.g., “Commercial Work”)
- [ ] Images have alternate text
- [ ] Good contrast & readable font sizes

## Where to Edit
- `index.qmd` — Home/About (includes portrait + resume button)
- `resume.qmd` — Resume page (download link)
- `projects.qmd` — Links to your commercial work
- `skills.qmd` — Skills & certifications
- `leadership.qmd` — Optional page included
- `contact.qmd` — Email + LinkedIn
- `reflection.qmd` — 300–500 words on LLM use
- `appendix.qmd` — LLM drafts + revisions + APA references

## Notes
- Cite all sources you use and clearly identify LLM‑generated content (done in Appendix).
- Resources: Quarto Docs, Spreed.chat, OpenAI, APA Style Guide.
