---
id: 2nag9m7euacuefvs78i12x6
title: Updating to GitHub
desc: ''
updated: 1677634955726
created: 1677616062151
---

## Updating dendron and published content

One major reason that `GitHub Pages` publishing with `GitHub Actions` is preferred, as opposed to this path, is that the GitHub Actions can automatically manage updates to your website.

If not using GitHub Actions, the following needs to be done whenever you'd like to publish a `new version` of your website.

> 1. rm -rf docs
> 2. rm -rf .next
> 3. rm -rf node_modules
> 4. rm -rf package*.json
> 5. npm install @dendronhq/dendron-cli@latest
> 6. npx dendron publish init
> 7. npx dendron publish export --target github

**If making to existing website, run the following commands**
> 1. git add .
> 2. git commit -m "<your msg here>"
> 3. git push