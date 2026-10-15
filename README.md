# Tahir Iqbal — Personal Portfolio Website

A responsive, static portfolio website with 34 project entries: 14 websites, 2 SaaS products, 5 ads reports, 3 SEO reports and 10 design collections.

## Deploy to Vercel (no code required)

1. Sign in to https://vercel.com/new.
2. Choose **Other / Deploy from template** or use Vercel CLI for direct deployment. The simplest reliable method is to upload this folder to a new GitHub repository, then **Add New → Project → Import Git Repository** in Vercel.
3. Framework preset: **Other**. Root directory: `/`. No build command; leave Output Directory empty.
4. Click **Deploy**. Vercel provides a `*.vercel.app` URL once the deployment succeeds.

The design is responsive and requires no npm packages. `index.html` loads `styles.css`, `script.js`, and `projects.json` from the same folder.

## Edit content

- Name, headings, navigation and contact CTA: `index.html`.
- Categories, project images, descriptions, live project URLs and metrics: `projects.json`.
- Layout/colors: `styles.css`.
- Filtering, modal, search and show more behavior: `script.js`.

**Important:** The source screenshots and website previews currently load from their publicly hosted original portfolio asset URLs. Keep the original asset hosting active, or replace the `image` URLs in `projects.json` and the hero image in `index.html` with images in a local `/images/` folder to make this site fully standalone. These screenshot URLs are not an affiliation or endorsement claim.

Performance snapshots reflect the reporting screenshots and their stated windows, not independently verified results. Do not aggregate overlapping periods.
