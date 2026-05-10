# Kindred Support Site

This folder is a ready-to-publish static site for `GitHub Pages`.

## Recommended Repo

Create a new public repository, for example:

- `app-support-site`
- `ankanghao-app-support`

Then copy the contents of this folder into that repository root.

## Suggested Structure

```text
app-support-site/
├── index.html
├── styles.css
└── kindred/
    ├── index.html
    └── privacy.html
```

## Before Publishing

Replace these placeholders in the HTML files:

- `YOUR_EMAIL@example.com`
- `https://github.com/YOUR_GITHUB_NAME/app-support-site`
- `YOUR_GITHUB_NAME`

## GitHub Pages

1. Push the files to the public repository.
2. Open `Settings` -> `Pages`.
3. Under `Build and deployment`:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
4. Save and wait a few minutes.

Your site URL will look like:

```text
https://YOUR_GITHUB_NAME.github.io/app-support-site/
```

## App Store Connect URLs

For Kindred, you can use:

- Support URL:
  `https://YOUR_GITHUB_NAME.github.io/app-support-site/kindred/`
- Privacy Policy URL:
  `https://YOUR_GITHUB_NAME.github.io/app-support-site/kindred/privacy.html`

## Optional Next Step

If you launch more apps later, keep adding folders:

- `/app-two/`
- `/app-three/`

This keeps all support and privacy pages in one public site.
