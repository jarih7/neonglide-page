# neonglide.github.io

A public support and privacy-policy page for the **NeonGlide** app on the App Store.

## Pages

| File | URL (once live) | Purpose |
|---|---|---|
| `index.html` | `/` | Support home – FAQ + contact |
| `privacy.html` | `/privacy.html` | Privacy policy |

## How to publish at `neonglide.github.io`

GitHub Pages serves a repository at `<username>.github.io` **only** when the repository is owned by a GitHub account (or organisation) named `<username>` and is named `<username>.github.io`.

### Steps

1. **Create (or use) a GitHub account / organisation named `neonglide`.**  
   If you already have one, skip this step.

2. **Transfer this repository to the `neonglide` account.**  
   Go to *Settings → Danger Zone → Transfer ownership* and enter `neonglide` as the new owner.  
   The repository will then live at `github.com/neonglide/neonglide.github.io`.

3. **Enable GitHub Pages.**  
   In the repository settings go to *Pages → Build and deployment* and set:
   - **Source**: Deploy from a branch  
   - **Branch**: `main` / `(root)`  
   Then click **Save**.

4. **Wait ~1 minute** for the first build to complete.  
   The site will then be live at **https://neonglide.github.io**.

> **Note:** The `.nojekyll` file in this repository tells GitHub Pages to serve the plain HTML files directly without running them through Jekyll, which is required for this site to work correctly.
