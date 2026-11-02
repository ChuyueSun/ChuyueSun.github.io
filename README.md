# Livia Sun — personal website

A static, responsive personal website. It needs no build step, server runtime, or third-party JavaScript. The portrait and BibTeX pages are stored locally so the site does not depend on Stanford hosting for those assets.

## Preview locally

Run `python3 -m http.server 8000` in this directory, then open `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a GitHub repository (for example, `ChuyueSun.github.io`) and push the files in this directory to its `main` branch.
2. In the repository, open **Settings → Pages** and select **Deploy from a branch**, `main`, `/ (root)`.
3. If the repository is named `ChuyueSun.github.io`, the site will be available at `https://chuyuesun.github.io/`. For another repository name, GitHub Pages uses `https://chuyuesun.github.io/<repository>/`.
4. For a custom domain, add it in **Settings → Pages**, then follow GitHub's displayed DNS instructions at your domain registrar. Add a `CNAME` file here containing the domain after you choose one.

The site uses relative internal links, so it works at either a root domain or a repository subpath. To update it, edit the HTML and CSS and push the changes.

Source content: [Stanford home page](https://web.stanford.edu/~chuyues/) and [research page](https://web.stanford.edu/~chuyues/Research.html), retrieved November 2, 2026. The current role and graduation date were supplied directly by Chuyue. Check the research list before publishing because the Stanford content may have changed.
