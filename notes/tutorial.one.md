---
id: 2nag9m7euacuefvs78i12x6
title: Updating to GitHub
desc: ''
updated: 1677634403499
created: 1677616062151
---

## Updating dendron and published content

One major reason that `GitHub Pages` publishing with `GitHub Actions` is preferred, as opposed to this path, is that the GitHub Actions can automatically manage updates to your website.

If not using GitHub Actions, the following needs to be done whenever you'd like to publish a new version of your website.

rm -rf docs
rm -rf .next
rm -rf node_modules
rm -rf package*.json
npm install @dendronhq/dendron-cli@latest
npx dendron publish init
npx dendron publish export --target github
git add .
git commit -m "Dendron page update"
git push