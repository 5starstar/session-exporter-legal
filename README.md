# session-exporter-legal

The public web pages for **Session Exporter for Claude Code (unofficial)**, published with GitHub Pages. The extension never loads or contacts these pages; the store listing links to them.

| File | What it is | Public address (after publishing) |
|---|---|---|
| `index.html` | Home page: what it is, screenshots, support, the optional tip link | https://5starstar.github.io/session-exporter-legal/ |
| `privacy.html` | **The privacy policy** (the address the store asks for) | https://5starstar.github.io/session-exporter-legal/privacy.html |
| `support.html` | Support: how to write, what to include, common questions | https://5starstar.github.io/session-exporter-legal/support.html |
| `404.html` | Shown by GitHub Pages for a wrong address | |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are (leave it, it is empty) | |
| `*.webp`, `icon.png` | Pictures used by the pages | |

## Publish (once)
1. On GitHub (account 5starstar) click **New repository**, name it exactly `session-exporter-legal`, set it to **Public**, create it.
2. On the new repository's page click **uploading an existing file** (or **Add file > Upload files**), drag in **everything from this folder** (including `.nojekyll`), then **Commit changes**.
3. **Settings > Pages**: Source **Deploy from a branch**, Branch **main**, folder **/ (root)**, **Save**.
4. Wait one or two minutes, then open the three addresses above. You must see the policy with the heading **"What it stores on your device"**.

## Change a page later
Open the file on GitHub, click the pencil (**Edit this file**), change it, **Commit changes**. Wait a minute, press Ctrl+F5.

**`privacy.html` is generated** from `store/PRIVACY.md` in the extension's source project (`npm run site`). If you change it here by hand, make the same change in `store/PRIVACY.md`, or the next generated version will undo yours.

## If you name the repository differently
The addresses above change (`https://5starstar.github.io/<name>/`). Update them in the store listing, and in `store/LISTING.md`, `store/chrome/SUBMISSION.md` and `store/chrome/STORE-PRIVACY-TAB-0_10_0.md` of the source project.
