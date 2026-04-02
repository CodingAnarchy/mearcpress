# Mearc Press

Static site for [mearcpress.com](https://mearcpress.com).

## Deploying to Cloudflare Pages

1. Push this repo to GitHub.
2. In the Cloudflare dashboard, go to **Workers & Pages → Create → Pages → Connect to Git**.
3. Select the GitHub repo.
4. Build settings:
   - **Build command:** (leave blank)
   - **Build output directory:** `/` (or leave blank)
   - **Framework preset:** None
5. Deploy.
6. In **Custom Domains**, add `mearcpress.com` and `www.mearcpress.com`.

Cloudflare handles SSL, CDN, and DNS automatically since the domain is on Cloudflare.

## Updating the site

Edit the HTML files and push to `main`. Cloudflare Pages will auto-deploy within seconds.

## Adding a book to the catalog

See the HTML comment template in `catalog.html` for the book card markup.
