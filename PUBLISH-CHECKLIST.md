# GitHub Pages Publish Checklist

Project folder:
- `C:\Users\DELL\Documents\FeedbackHub`

## 1. Create a GitHub repository
1. Open [https://github.com/new](https://github.com/new)
2. Repository name: `feedbackhub` (or any name you prefer)
3. Visibility: Public (recommended for easiest free hosting)
4. Click **Create repository**

## 2. Upload this project
1. Open your new repository page
2. Click **uploading an existing file**
3. Drag and drop everything inside `C:\Users\DELL\Documents\FeedbackHub`
   - Include: `index.html`
   - Include: `.github/workflows/deploy-pages.yml`
4. Commit message: `Initial site upload`
5. Click **Commit changes**

## 3. Enable GitHub Pages via Actions
1. Open your repo: **Settings** -> **Pages**
2. Under **Build and deployment**, choose **Source: GitHub Actions**

## 4. Wait for deployment
1. Open the **Actions** tab
2. Wait for workflow: `Deploy static site to GitHub Pages` to finish (green check)

## 5. Open your live site
- URL format:
  - `https://<your-username>.github.io/<repo-name>/`
- Example:
  - `https://johnkato.github.io/feedbackhub/`

## Notes
- Every new commit to `main` automatically republishes your site.
- Hosting on GitHub Pages is free.
