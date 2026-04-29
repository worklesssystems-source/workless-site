# Workless SEO Fixes — Deploy Checklist

Files in this folder → copy each one to the ROOT of your GitHub Pages repo.

## Step 1 — Copy these 2 files to repo root (no edits needed)

- robots.txt      → repo root
- sitemap.xml     → repo root

## Step 2 — Update index.html <head>

Open index.html. Find everything between <head> and </head> and replace it with
the content from index-head.html.

IMPORTANT: Keep your existing <style>...</style> block exactly where the comment
"PASTE YOUR EXISTING <style> BLOCK HERE" appears. Just copy your style block there.

## Step 3 — Update contact.html <head>

Same as Step 2 but using contact-head.html as the source.

## Step 4 — Create an OG image (1200×630px)

Both pages reference /og-image.jpg. Create a 1200×630px image showing:
- Workless Systems brand (orange + black)
- Tagline: "Automatizări AI pentru Afaceri"
- Save as og-image.jpg and upload to repo root

## Step 5 — Create favicons

Need 3 files in repo root:
- favicon-16.png  (16×16px, orange W logo)
- favicon-32.png  (32×32px, orange W logo)
- apple-touch-icon.png (180×180px, orange W logo with padding)

Free tool: https://realfavicongenerator.net/

## Step 6 — Set up Google Search Console

1. Go to https://search.google.com/search-console
2. Add property → URL prefix → https://workless.ro
3. Verify ownership (easiest: HTML file upload to repo root)
4. Go to Sitemaps → add: sitemap.xml
5. Use URL Inspection tool → request indexing for:
   - https://workless.ro/
   - https://workless.ro/contact.html

## Title changes (optional but recommended)

index.html title was changed from:
  "Workless Systems — Automatizări AI"
to:
  "Automatizări AI pentru Afaceri | Workless Systems România"

This adds keywords while keeping the brand name. Revert if you prefer the original.

## What was NOT changed

- All existing <style> CSS (unchanged)
- All HTML body content (unchanged)
- All JavaScript (unchanged)
- Site structure (unchanged)
