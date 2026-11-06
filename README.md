# GyanSetu — free book launch website

A responsive static website for **Class XII Computer Science – 1000 Questions & Answers (Session 2026–27)** by Harshvardhan Singh.

## Included
- Responsive landing page for desktop and mobile
- Book cover artwork
- Overview and all 12 lesson titles
- Free PDF download (included in `downloads/`)
- Author section and RBSE/government non-affiliation disclaimer
- No payment gateway or paid-download flow; this launch edition is presented as a free educational resource

## Preview locally
Open `index.html` in a browser. For a local web server, run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Deploy with Cloudflare Pages
1. Create a GitHub repository, for example `gyansetu`.
2. Upload all files and folders from this project to the repository root.
3. In Cloudflare Dashboard, open **Workers & Pages → Create → Pages → Connect to Git**.
4. Select the repository. Since this is a static HTML site, leave the build command blank and set the output directory to `/` (repository root).
5. Deploy. Cloudflare will provide a `*.pages.dev` preview URL.
6. After testing, connect your custom domain in the Pages project under **Custom domains**. The previously selected domain was `[domain to be selected]`; it was not yet purchased as of the last confirmed setup, so purchase it before attempting to connect it.

## Before public launch
- Confirm the PDF is the final approved edition and that you have permission to publish its contents.
- Test the download on desktop and mobile.
- Add a privacy/contact page if you later collect visitor information or forms.
- This is an independent supplementary resource, not an official RBSE or government publication.


Brand assets: `assets/gyansetu-logo.png`, `favicon.png`, and author portrait `assets/harshvardhan-singh.jpg`. The logo and favicon are included in the site header and browser tab; the author portrait appears in the About the Author section.
