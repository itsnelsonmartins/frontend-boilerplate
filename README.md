# Vite + React + Sass + Typescript

### HOWTO

Create github repository

    git init
    git add README.md
    git commit -m 'First commit'
    git branch -M main
    git remote add origin git@github.com:GITHUB_USERNAME/REPO_NAME.git
    git push -u origin main

Change base in vite.config.ts to match REPO_NAME

    base: '/frontend-boilerplate/'

### Enable Pages Github Actions

-   Settings > Pages
-   Build and deployment
    -   Source
        -   Github Actions
