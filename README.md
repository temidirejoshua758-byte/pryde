# PRYDE — Own Your Presence.

A responsive, multi-page static website concept for a men's executive clothing and accessories brand. Built with HTML, CSS and vanilla JavaScript; no paid hosting or build tools required.

## Pages
- `index.html` — home page with cinematic visual banner
- `collections.html` — four main collections
- `clothing.html` — suits/jackets, shirts, trousers, neckwear and layering
- `footwear.html` — formal leather shoes and smart-casual footwear
- `leather-goods.html` — belts, wallets/small leather accessories and executive bags
- `accessories.html` — watches, suit accessories and finishing accessories
- `lookbook.html`, `about.html`, `contact.html`

## Publish free with GitHub Pages
1. Sign in to GitHub and create a **new public repository** named `pryde` (or another name you prefer).
2. Download and unzip this project on your computer.
3. Open the unzipped `pryde-website` folder. Upload its **contents** to the repository root (not the folder itself). Make sure `index.html`, `styles.css`, `site.js`, `assets/`, and `.github/` are at the top level.
4. Commit the files to the `main` branch.
5. Open the repository's **Settings → Pages**. Under Build and deployment, select **GitHub Actions** as the source. The included workflow deploys the site after a push.
6. Open the **Actions** tab and wait for **Deploy PRYDE website to GitHub Pages** to finish successfully.
7. Your free website address will look like `https://YOUR-GITHUB-USERNAME.github.io/pryde/` (replace the username and repository name with yours).
8. When you update files later, commit/push again; the workflow republishes the site.

### Important if you use an existing repository
This project includes its own `index.html`, `styles.css`, `site.js`, `assets/` and `.github/workflows/pages.yml`. Upload/replace these in the repository you want to use. Do not mix it into your Choplicious site unless you intend to replace that site's homepage. For a separate PRYDE website, a separate repository is recommended.

## Before launch
- The hero uses a remote video URL with the generated hero image as a poster/fallback. If the video provider blocks playback or changes the URL, the image still displays; for dependable playback, use a licensed video file you own and place it in `assets/`.
- Product photographs are illustrative remote Unsplash images, and several styles share editorial imagery. Replace these with your own accurate product photography before selling products.
- The contact page currently opens the visitor's email application and uses `hello@pryde.example` as a placeholder. Replace it in `site.js` and `contact.html` with your real business email.
- The newsletter form is a visual demo and does not collect or store addresses. Connect a newsletter provider if you need subscriptions.
- No prices, stock, checkout or payment processing are invented/included. Add verified product details and a trusted payment service when you are ready to sell.

## Customise product images
The collection data and product names live in `site.js` near the top. `IMAGES` holds image IDs used for each category; `urlFor()` builds the Unsplash image URL. Replace those IDs/URLs with photos you own or are licensed to use. The website is static, so changes can be made directly in GitHub's file editor or uploaded from your computer.
