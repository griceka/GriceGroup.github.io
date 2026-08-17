# Kyle A. Grice — GitHub Pages website

This is a static HTML/CSS academic website designed for GitHub Pages.

## Before publishing
1. Replace the photo placeholder with a real image in `assets/`.
2. Replace `REPLACE_WITH_YOUR_DEPAUL_EMAIL` in `contact.html` (already set to `kgrice1@depaul.edu`).
3. Put your current CV at `documents/Grice_CV.pdf`.
4. Review the publication page and add publications #1–18 and the non-peer-reviewed teaching resources.
5. Replace placeholder Google Scholar/Bluesky/LinkedIn/ResearchGate URLs with your exact profiles.
6. Review all DePaul links before publishing.

---

## Preview the site locally (easy, no coding required)

Option A — Open the files directly (simplest)
- Download a copy of the repository as a ZIP from GitHub (Code → Download ZIP) and unzip it.
- Double-click index.html to open it in your web browser (Chrome, Firefox, Safari will work).
- This is the quickest way to preview the pages, but in a few cases (for example if some files are loaded by a small local server) you may see broken images or links. If that happens, try Option B below.

Option B — Clone the repo and open locally (recommended, still simple)
- Install GitHub Desktop (download from https://desktop.github.com/) or use the GitHub web UI to download the files.
- In GitHub Desktop: File → Clone repository → choose `griceka/GriceGroup.github.io` → Clone.
- In your file browser, open the cloned folder and double-click index.html to view.

Option C — Run a tiny local web server (one command; helpful for some browsers)
- If you have Python installed (many Macs/Windows have it), open Terminal (macOS) or Command Prompt / PowerShell (Windows) and run:

  python3 -m http.server 8000

- Then open http://localhost:8000 in your browser. Press Ctrl+C in the terminal to stop the server.

If you want a "live reload" preview while you edit, a free tool is the "Live Server" extension in Visual Studio Code; I can help set that up if you'd like.

---

## How to publish the site on GitHub Pages (simple steps)

A. Publish as a project site (current repo name)
- Go to your repository on GitHub: https://github.com/griceka/GriceGroup.github.io
- Click Settings → Pages (left sidebar).
- Under "Build and deployment" or "Source", select the branch to publish (choose `main`) and the folder `/(root)`.
- Save. GitHub will show the site URL — usually in a few minutes your site will be live at something like:

  https://griceka.github.io/GriceGroup.github.io/

B. (Optional) Make this your user site (served at https://griceka.github.io)
- If you prefer the simpler URL https://griceka.github.io you need your repository to be named exactly `griceka.github.io`.
- You can rename the repository (Settings → Repository name) to `griceka.github.io`. After renaming, repeat the Pages steps above (branch `main` + root) and your site will be served at https://griceka.github.io.
- Note: renaming a repo is safe but may change links; I can help do this and update links if you want.

C. Custom domain (not requested now)
- If you later want a custom domain (your own URL), you can add a file named `CNAME` with the domain in the repository root and configure DNS. I can help with that setup.

---

## Terms explained (plain language)

- Repository (repo): a folder stored on GitHub where your website files live. Example: `griceka/GriceGroup.github.io`.
- Branch: a copy of the site files where we can make changes without affecting the main live copy. You already have `feature/add-site` for editing and `main` as the default. Think of a branch as a draft area.
- Commit: a saved change. When I edit files I "commit" those changes (like saving a version).
- Pull request (PR): a formal request to merge changes from one branch into another (for review). I can open a PR so you can review my edits before they become live.
- Merge: applying the changes from a PR into the main branch so they become the new live files.
- Default branch: the main branch of the repo, usually `main` or `master`. GitHub Pages will publish from whichever branch you choose in Settings.

---

## What I did for you on the `feature/add-site` branch
- Added a `.nojekyll` file (prevents GitHub from trying to process the site with Jekyll) so your plain HTML/CSS is served as-is.
- Updated `contact.html` to use your email (kgrice1@depaul.edu).
- Added these preview and publish instructions to the README so you have a simple reference.

When you're ready, I can open a Pull Request so you can review the changes. I will not merge or publish anything unless you tell me to.
