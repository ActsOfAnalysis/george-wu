# George (Zuojun) Wu: personal website (Quarto)

## Edit
- index.qmd: About, skills, education, certifications. Fill in the TODO links (Google Scholar, email).
- experience.qmd and publications.qmd: other pages.
- Photo: put your photo at images/profile.jpg, then change `image:` in index.qmd to images/profile.jpg.
- After any edit: RStudio > Build tab > Render Website (or run `quarto render` in Terminal). This updates the docs/ folder.

## Publish on GitHub Pages (one time)
1. Create a free account at github.com.
2. Create a new public repository named YOUR-USERNAME.github.io.
3. Upload this whole folder (Add file > Upload files, drag everything in, including docs/), then Commit.
4. Repository Settings > Pages > Source: "Deploy from a branch", Branch: main, Folder: /docs > Save.
5. After 1-2 minutes, the site is live at https://YOUR-USERNAME.github.io
6. In _quarto.yml, replace YOUR-GITHUB-USERNAME in site-url.

## Update later
Edit, render, and upload the changed files (or push with Git from RStudio).
