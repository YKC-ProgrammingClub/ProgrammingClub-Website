# Git Workflow

## Golden Rule
**Never push directly to `main`.** All changes go through a branch and a Pull Request (PR).

## Step-by-Step Workflow
1. **Sync `main`:**
   in bash shell:
    git checkout main
    git pull origin main

2. **Create a branch for your task:**
    in bash shell:
     git checkout -b <type>/<short-description>

   Examples:
   - `git checkout -b feat/project-filter`
   - `git checkout -b style/faq-layout`
   - `git checkout -b docs/starter-resources`

3. **Stage and commit your work:**
    in bash shell:
     git add .
     git commit -m "feat: add category filter to project showcase"


4. **Push your branch:**
    in bash shell:
     git push -u origin <your-branch-name>


5. **Open a Pull Request:**
   - Go to GitHub, open a PR from your branch into `main`, fill out the PR template, and request a review.
   - After approval and merge, switch back to `main` and run `git pull origin main`.

## Branch Naming
- `feat/<name>` — new features or sections
- `fix/<name>` — bug fixes
- `style/<name>` — CSS/layout/visual updates
- `docs/<name>` — documentation or text content updates
- `refactor/<name>` — code cleanup without changing behavior