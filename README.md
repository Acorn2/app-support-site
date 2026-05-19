# Acorn2 App Support Site

This repository is a ready-to-publish static support site for `GitHub Pages`.
It is intended for App Store submission materials such as app support pages,
privacy policies, and a shared homepage that can scale across multiple iOS
apps.

## Repository

- GitHub: `https://github.com/Acorn2/app-support-site`
- Publisher contact: `hkyy521@163.com`
- Recommended Pages URL: `https://acorn2.github.io/app-support-site/`
- Current live app folders: `kindred/`, `linkbox/`

## Suggested Structure

```text
app-support-site/
├── index.html
├── styles.css
├── linkbox/
│   ├── index.html
│   └── privacy.html
└── kindred/
    ├── index.html
    └── privacy.html
```

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
https://acorn2.github.io/app-support-site/
```

## App Store Connect URLs

For Kindred:

- Support URL:
  `https://acorn2.github.io/app-support-site/kindred/`
- Privacy Policy URL:
  `https://acorn2.github.io/app-support-site/kindred/privacy.html`

For LinkBox:

- Support URL:
  `https://acorn2.github.io/app-support-site/linkbox/`
- Privacy Policy URL:
  `https://acorn2.github.io/app-support-site/linkbox/privacy.html`

## Included Pages

- Home page: app support directory for current and future apps
- `kindred/index.html`: Kindred support page
- `kindred/privacy.html`: Kindred privacy policy
- `linkbox/index.html`: LinkBox support page
- `linkbox/privacy.html`: LinkBox privacy policy

## App Review Notes

- Support contact email is `hkyy521@163.com`
- GitHub repository name is `Acorn2/app-support-site`
- Kindred privacy policy effective date is `May 10, 2026`
- LinkBox privacy policy effective date is `May 19, 2026`

## Adding Another App

When you launch another app later, follow the same pattern:

1. Create a new folder such as `/next-app/`.
2. Add `index.html` for support and `privacy.html` for the privacy policy.
3. Reuse `../styles.css` so the visual system stays consistent.
4. Add the new app card and URLs to the homepage `index.html`.
5. Submit the final support and privacy URLs in App Store Connect.

This keeps all support and privacy pages in one public site with the same UI
language and a predictable submission structure.
