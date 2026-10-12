# Chindu Esuru Portfolio — Publish and Update Guide

This folder contains the editable portfolio webpage and its profile image.

## Publish it publicly with GitHub Pages

1. Sign in to GitHub and create a **new public repository** (for example, `chindu-esuru-portfolio`).
2. Extract this ZIP on your computer.
3. Upload `index.html` and the `assets` folder (including `profile.webp`) to the top level of the repository.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**. Choose branch **main** and folder **/(root)**, then select **Save**.
6. After GitHub finishes publishing, the Pages section will show your public website address. For a repository called `chindu-esuru-portfolio`, it usually follows this pattern: `https://YOUR-GITHUB-USERNAME.github.io/chindu-esuru-portfolio/`.
7. Open the website address in a private/incognito browser window to check that visitors can view it without signing in.

GitHub's official instructions: https://docs.github.com/en/pages/quickstart and https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Update it later

- **Change text or colors:** Open `index.html` in a text editor, make your changes, save it, and upload the updated file to the same repository, replacing the old `index.html`.
- **Change the portrait:** Replace `assets/profile.webp` with the new image, keeping the same filename and folder path.
- Commit the changed files to the `main` branch. GitHub Pages will publish the update automatically; allow a few minutes, then refresh your website.
- Keep the image file and `index.html` together in the same structure so the portrait keeps displaying.

For the free GitHub Pages option, the repository must be public. A Pages site is publicly viewable, so only include contact details you want visitors to see.
