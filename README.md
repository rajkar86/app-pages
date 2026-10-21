# app-pages

Public privacy policy and support pages for Karthik's apps. Plain HTML and one shared `style.css`. No JavaScript, no trackers, no external fonts.

Target address once published: https://rajkar86.github.io/app-pages/

## Layout

- `index.html`: lists the apps.
- `style.css`: shared style, light and dark mode.
- `<app>/privacy/index.html` and `<app>/support/index.html`: one folder per app.

## Add an app

1. Copy the `spelling-bee` folder to a new folder named after the app (lowercase, hyphens).
2. Edit the text in `privacy/index.html` and `support/index.html`. Keep the `../../style.css` links.
3. Add a list item for the app in the root `index.html`.
4. Open the pages in a browser, check a phone width and dark mode, then commit.

## Publish (not done yet)

1. Create a public repo `rajkar86/app-pages` on GitHub.
2. Add it as `origin` and push `main`.
3. In the repo settings, open Pages and choose Deploy from a branch: `main`, folder `/ (root)`.
4. Check https://rajkar86.github.io/app-pages/spelling-bee/privacy/ and https://rajkar86.github.io/app-pages/spelling-bee/support/.
5. Paste those two URLs into App Store Connect.

## Open

- Copyright line: name not decided. Search for `TODO` in the HTML files.
