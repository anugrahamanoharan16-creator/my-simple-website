# My CI/CD Website

A simple static website deployed automatically using **GitHub Actions** + **GitHub Pages**.

[![Deploy Website CI/CD](https://github.com/anugrahamanoharan16-creator/my-simple-website/actions/workflows/deploy.yml/badge.svg)](https://github.com/anugrahamanoharan16-creator/my-simple-website/actions)

## Live demo
The site is published at:
`https://anugrahamanoharan16-creator.github.io/my-simple-website/`

> Note: If the site is not live immediately, open **Settings → Pages** and confirm the site status after a successful workflow run.

## What this project contains
- `index.html` — simple site with Bootstrap
- `.github/workflows/deploy.yml` — GitHub Actions workflow that deploys to GitHub Pages

## How it works (short)
1. Push changes to `main`  
2. GitHub Actions builds/upload the site artifact  
3. `actions/deploy-pages` publishes the artifact to GitHub Pages

## Next-step ideas
- Add HTML linting (CI check)  
- Add performance check or unit tests (if using a build step)  
- Add a custom domain

## CI/CD Diagram
Developer → GitHub Repo → GitHub Actions → GitHub Pages → Live Site

---

Made by Anugraha • GitHub Actions • GitHub Pages
