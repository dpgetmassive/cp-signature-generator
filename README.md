# Cyber People — Email Signature Generator

A single-page app that generates Outlook-safe HTML email signatures for the Cyber People team.

Fill in the form, preview live, then copy or download the signature HTML.

## Adding the Logo

Drop your logo PNG into the `images/` folder as `logo.png` (recommended size: 200x60 px).

The signature HTML references `images/logo.png` — when deploying, make sure the image is accessible at that relative path. For production signatures, replace the `src` with a full URL (e.g. `https://your-org.github.io/repo-name/images/logo.png`) so the logo displays in email clients.

## Deploy to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Set source to the branch (e.g. `main`) and folder (`/ (root)`).
4. The site will be live at `https://<org>.github.io/<repo>/`.

## Local Use

Open `index.html` in any browser — no server or build step required.
