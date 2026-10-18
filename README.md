# PlayNova BD — Demo Gaming Website

A responsive, front-end-only gaming website prototype with a yellow-and-white design inspired by common mobile gaming dashboards.

## Run locally
1. Download and extract `playnova-bd-demo.zip`.
2. Open `index.html` in a modern browser.
3. For editing, open the folder in VS Code or another code editor.

## Publish using GitHub Pages
1. Create a GitHub repository named `playnova-bd`.
2. Upload `index.html`, `style.css`, `app.js`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site; the URL appears in the Pages section.

## Demo-only behavior
- Demo balance starts at ৳1,000.
- Add/use-credit buttons change only the in-memory browser demo balance.
- No real payments, withdrawals, accounts, passwords, or payment details are processed.
- Refreshing the page resets the demo balance to its initial amount.
- Game cards are UI previews, not real gambling games.

## Customize
- Change the site name in `index.html`.
- Change colors and layout in `style.css` (`--yellow`, `--ink`, etc.).
- Add or edit demo game cards in the `games` array in `app.js`.

For a production service, add appropriate security, privacy notices, legal review, and server-side systems. Never collect payment credentials in a static demo page.
