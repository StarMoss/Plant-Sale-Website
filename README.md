# Plant Sale — GitHub Pages starter project

A one-page, mobile-friendly plant catalog. It uses only HTML, CSS, and a tiny bit of JavaScript—no framework, build step, database, or checkout.

[Plant Sale Website](https://starmoss.github.io/Plant-Sale-Website/)

## Files

- `index.html` — the website and all 30 editable plant cards
- `images/` — put your plant photos here

## Customize the listings

For each plant card in `index.html`:

1. Replace `Plant name 01` with the plant name.
2. Replace `$—` with a price, such as `$12`.
3. Replace the placeholder description with your own short description.
4. Add the matching photo in `images/`, named `plant-01.jpg`, `plant-02.jpg`, and so on.
5. If you have a photo with a different filename, update that card's `src="images/plant-01.jpg"` to match.
6. To mark a plant sold, change the card's `data-status="available"` to `data-status="sold"` and change the visible badge from `Available` to `Sold`.

If you don't need all of the slots, delete any complete `<article class="plant-card" ...> ... </article>` block. If you need more, copy a complete card and update its image number and listing details.

**Image tips:** Use `.jpg`, `.jpeg`, `.png`, or `.webp` filenames consistently. Resize very large phone photos to about 1200 pixels on the longest edge to make the page load faster. Filenames are case-sensitive on GitHub Pages.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new repository named `plant-sale`.
2. For the simplest setup, make the repository **Public**. (GitHub Pages availability and settings can depend on your plan.)
3. Upload `index.html`, `README.md`, and the whole `images` folder to the repository root.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then click **Save**.
7. Wait a minute or two, then visit the URL GitHub shows. For a repository named `plant-sale`, it will usually look like `https://YOUR-USERNAME.github.io/plant-sale/`.
8. Open that link on your phone and check a few cards before sharing it.

## Make changes or take the site down

Edit `index.html` and upload/commit the updated file. Changes generally publish automatically after GitHub Pages finishes deploying.

When the sale is over, go to **Settings → Pages** and disable publishing, or delete the temporary repository if you no longer need it.

## Privacy note

GitHub Pages is public hosting, not password-protected sharing. Anyone with the link can view the page, and a public repository also exposes the site source and uploaded photos. Don't include your home address or other personal details unless you intend to share them.
