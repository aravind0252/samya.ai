# Samya Website - Setup & Hosting Guide

This directory contains the source code for the Samya website.

## 1. Preview Locally

To view the website on your local machine:

1.  Open the `index.html` file in your browser.
    OR
2.  Run a local server (recommended):
    ```bash
    python3 -m http.server 8000
    ```
    Then open `http://localhost:8000` in your browser.

## 2. Host on GitHub Pages

Follow these steps to publish your site for free:

### Step A: Create a Repository
1.  Go to [GitHub.com](https://github.com) and log in.
2.  Click the **+** icon in the top right and select **New repository**.
3.  Name it `samya-website` (or `samya` if you want it to be your main project page).
4.  Make sure it is **Public**.
5.  Click **Create repository**.

### Step B: Push Code
Open your terminal in this folder (`/home/ananth/ai-workspace/samya`) and run:

```bash
git init
git add .
git commit -m "Initial commit: Samya website launch"
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/samya-website.git
git push -u origin main
```
*(Replace `<YOUR-USERNAME>` and `samya-website` with your actual GitHub username and repo name)*

### Step C: Enable GitHub Pages
1.  Go to your repository on GitHub.
2.  Click **Settings** > **Pages** (on the left sidebar).
3.  Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4.  Under **Branch**, select **main** and folder **/(root)**.
5.  Click **Save**.

Your site will be live at `https://<YOUR-USERNAME>.github.io/samya-website/` within a few minutes!
