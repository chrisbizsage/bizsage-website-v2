# BizSage website

Static one-page site for [bizsage.co.za](https://bizsage.co.za): AI operations for South African companies, led by Chris Irwin.

No build step. Vercel serves the files as they are.

## Structure

```
index.html            The page (HTML, CSS and a small script, all inline)
assets/               Photo, logo mask, logo PNGs, social share image
favicon.ico, *.png    Favicons and app icons
site.webmanifest      Icon manifest
robots.txt, sitemap.xml
vercel.json           Clean URLs, caching and security headers
```

## Deploy on Vercel

1. In Vercel, choose **Add New → Project** and import `chrisbizsage/bizsage-website`.
2. Framework preset: **Other**. Leave the build command and output directory empty.
3. Deploy. Every push to `main` redeploys automatically.
4. Add the domain under **Settings → Domains**: `bizsage.co.za` and `www.bizsage.co.za`, then update DNS as Vercel instructs.

## Before going live

- Replace the placeholder email `chris@bizsage.co.za` in `index.html` if needed, or swap in a booking link.
- Check the founder track record lines in the "Who we are" section.

## Local preview

```
npx serve .
```
