# Mic Test Pro — static site replacement

This folder contains a static HTML replacement for https://mic-testpro.vercel.app/.

## Files
- `index.html` — microphone tester and original troubleshooting content
- `about.html`
- `privacy-policy.html`
- `terms.html`
- `contact.html`
- `robots.txt`
- `sitemap.xml`
- `ads.txt`

## Deploy
Upload these files to the root of the existing GitHub repository connected to Vercel. Keep the repository's current static-site deployment configuration unless you know it is unnecessary. Vercel should redeploy after the commit.

## Before submitting/reviewing with AdSense
1. Test microphone permission, level meter, recording/playback, stop button, and mobile layout in current browsers.
2. Open each legal page and `https://mic-testpro.vercel.app/robots.txt`, `/sitemap.xml`, and `/ads.txt` on the live site.
3. Confirm the privacy policy reflects the analytics/advertising tools actually enabled on the deployed site.
4. Submit the sitemap in Google Search Console and check indexing/crawl status.
5. Do not add ad slots or assume ads are approved just because the AdSense loader and `ads.txt` are present.

The privacy and terms pages are general templates and should be reviewed for your actual practices and legal requirements.
