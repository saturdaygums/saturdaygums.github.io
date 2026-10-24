# Saturday Gums website

A responsive, static website for Saturday Gums and Agro Processing Pvt Ltd. The site is built with HTML, CSS, and a small JavaScript file; it has no build step or package dependencies.

## Run locally

Open `index.html` in a browser, or serve the repository root with any static web server.

## Publish with GitHub Pages

1. Push the site files to the repository's `main` branch.
2. In the repository, open **Settings → Pages** and select **Deploy from a branch**, then choose `main` and the `/ (root)` folder.
3. The repository's `CNAME` file configures the custom domain `saturdaygums.com`. Confirm the domain's DNS records point to GitHub Pages and enable HTTPS in the Pages settings.

GitHub Pages serves `index.html` directly; no compilation or deployment workflow is required.

## Website features

- Responsive navigation and layouts for mobile and desktop.
- Application, certification, company, and FAQ sections.
- Contact form submitted through FormSubmit to `info@saturdaygums.com`.
- Embedded Google Map for the Dhule office.
- Search-friendly page title, description, canonical URL, social sharing metadata, and Organization structured data.
- `robots.txt` and `sitemap.xml` for search crawler discovery.

The form, map, and Google Fonts use external services and require an internet connection.

## SEO and free search visibility

The site is prepared for crawling, but publishing these files does not guarantee indexing or a particular ranking. Google chooses when and where pages appear; a one-page site will be most competitive for relevant, specific searches rather than every broad guar gum query.

### Target search phrases

These are relevant search-intent phrases based on the company's products and applications, not verified keyword-volume or ranking data:

- guar gum manufacturer in India
- guar gum powder manufacturer in India
- guar gum derivatives manufacturer
- guar gum for food industry
- guar gum for pharmaceutical applications
- guar gum for textile and paper industry
- guar gum manufacturer in Maharashtra

Use the phrases naturally in accurate page copy. Do not add a keyword-stuffed `meta keywords` tag; Google Search does not use it for ranking. To prioritize by actual demand, use the free Google Ads Keyword Planner and refine these candidates using real Search Console query data.

### After publishing

1. Confirm `https://saturdaygums.com/` loads over HTTPS and redirects consistently to the canonical domain.
2. Create a Google Search Console **Domain** property for `saturdaygums.com`, verify it by adding the DNS record Google provides, and submit `https://saturdaygums.com/sitemap.xml`.
3. Use Search Console's URL Inspection tool to request indexing of the homepage and check for crawl or indexing issues. Review Search results performance over time before changing page copy.
4. Claim or create the free [Google Business Profile](https://www.google.com/business/) if the business is eligible. Verify the listing, and keep its business name, address, phone, hours, and website consistent with the real business. Add genuine facility/product photos and respond to reviews.
5. Keep `sitemap.xml` current if additional pages are added. Create useful, original pages for products or applications only when verified product specifications and customer information are available.

See Google's [SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) and [sitemap documentation](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap) for current guidance. Search Console setup and Business Profile verification require access to the company's Google account and domain DNS; they cannot be completed in this repository.
