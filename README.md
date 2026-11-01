# Deer Research Site

A modern, kid-friendly website about deer, their forest habitat, and fun facts — built as a multi-page research project site for a third grader.

## Pages

- **Home** (`index.html`) — welcome page and navigation hub
- **About Deer** (`about.html`) — what deer are, why they matter
- **Species** (`species.html`) — white-tailed deer, mule deer, elk, moose, caribou
- **Habitat** (`habitat.html`) — forests, fields, and where deer live
- **Behavior** (`behavior.html`) — daily routines, movement, social groups
- **Food** (`food.html`) — what deer eat across the seasons
- **Fun Facts** (`fun-facts.html`) — surprising facts for the project
- **Resources** (`resources.html`) — citeable sources, books, and videos
- **Safety** (`safety.html`) — safe ways to observe deer in the wild

## Deploying to GitHub Pages

This repo ships with a GitHub Actions workflow (`.github/workflows/deploy.yml`) that deploys the site to GitHub Pages automatically whenever you push to `main`.

To enable it (one-time, in the browser):

1. In your repository, go to **Settings → Pages**.
2. Under "Source", select **Deploy from a branch**.
3. Choose the branch and select **`/docs` (GitHub Pages)** is NOT what we use — instead set source to **GitHub Actions** (labelled "Deploy from GitHub Actions").
4. Wait ~1 minute for the workflow to finish; the site will be live at:

```
https://<your-username>.github.io/<repo-name>/
```

After that, every `git push` redeploys the site automatically.

### Quick deploy check

The workflow builds a clean `site/` folder containing all `*.html` files plus `style.css` and uploads it as the Pages artifact.

## Images

All deer images are hot-linked to public Wikimedia Commons URLs (verified working). No images are downloaded or stored in the repo, keeping it lightweight.

## Citing sources

See the **Resources** page for books, articles, and websites the project can cite.

## Live Site

Once GitHub Pages is enabled (Settings → Pages → Deploy from GitHub Actions), the site is served at:

https://nlpzach.github.io/deer-research-site/

Any push to main automatically redeploys the site.
