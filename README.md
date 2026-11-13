# APES Recall Lab — GitHub Pages package

This is a build-free, responsive, offline-capable progressive web app for APES 2020 Practice Exam #2 cumulative answer-recall practice.

## Deploy (GitHub Pages)

1. Create a repository on GitHub, preferably named `apes-recall-lab`.
2. Unzip `APES_Recall_Lab_GitHub_Pages.zip`. Upload **the files inside**, not the ZIP as a file, to the root of your repository. Commit on branch `main`.
3. Repo → **Settings** → **Pages** → **Build and deployment** → **Deploy from a branch** → `main` and `/(root)` → Save.
4. Open `https://<username>.github.io/apes-recall-lab/` after Pages finishes publishing. For a different repository name, replace the final URL segment.
5. Open in iPhone Safari once online and use Share → **Add to Home Screen**. Test Airplane Mode before using offline.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Features

- Starts at Q1–40, with previous perfect recall through Q1–35.
- Every new cumulative round always begins at Q1; increments by five.
- Correctness by individual question, wrong-position review, `X` as unsure.
- Saves progress in this browser; export/import JSON across devices/sites.
- No ads, sign-in, analytics, remote data or ChatGPT dependencies.

**Public site warning:** The answer sequence is embedded in `index.html` and thus publicly visible to anyone visiting the site. Only deploy content you have the right to publish.

## Offline note

Uses service-worker caching and requires an online first load. GitHub Pages HTTPS allows service workers on supported browsers.
