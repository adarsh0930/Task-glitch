# Manual Deployment Guide

We have configured the project for manual deployment using `gh-pages`. This means you can deploy the site directly from your computer without committing any workflow files.

## Prerequisites
- You must be authenticated with GitHub on your local machine (which you are).

## How to Deploy
Run the following command in your terminal:

```bash
npm run deploy
```

## What this does
1.  **Builds the project**: It runs `npm run build` to create a production-ready `dist` folder.
2.  **Deploys to GitHub**: It pushes the `dist` folder to the `gh-pages` branch on your GitHub repository.

## Final Step (One-time)
After the first successful deployment:
1.  Go to your GitHub repository **Settings** -> **Pages**.
2.  Ensure **Source** is set to `Deploy from a branch`.
3.  Ensure **Branch** is set to `gh-pages` / `/ (root)`.
4.  Save if necessary.

Your site will be live at: https://adarsh0930.github.io/Task-glitch/
