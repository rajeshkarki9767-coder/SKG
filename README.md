# Skin Care Guide Nepal (SKG)

Evidence-based skincare blog for Nepal and global skin types, with a companion routine tracker app.

🌐 **Live site:** https://skincareguide-skg.vercel.app  
📱 **App:** https://skincareguide-skg.vercel.app/app.html

---

## What's Inside

- **38 articles** (~102,000 words) covering Nepal-specific and global skincare
- **SKG Routine Tracker app** with Manage / Guide tabs, theme picker, product shelf
- **AdSense-compliant** static site with banner + sticky ads
- **PWA-ready** with manifest and apple-touch-icon
- **SEO-optimised** with sitemap, robots.txt, JSON-LD schema, canonical URLs

---

## Tech Stack

- **Pure HTML / CSS / JavaScript** — no build step, no dependencies
- **Vercel** — static hosting with `vercel.json` for security headers and clean URLs
- **Google AdSense** — banner ads (banner + sticky) and Auto Ads vignette (after approval)
- **Google Analytics 4** — page view tracking (replace placeholder ID before deploy)

---

## File Structure

```
.
├── index.html              # Blog homepage
├── app.html                # SKG routine tracker app
├── about.html              # About page
├── author.html             # Author bio (Thunder Anuprayog)
├── contact.html            # Contact form
├── privacy-policy.html     # Privacy policy with AdSense disclosure
├── style.css               # Blog stylesheet
├── manifest.webmanifest    # PWA manifest
├── sitemap.xml             # SEO sitemap (43 URLs)
├── robots.txt              # Crawler directives
├── ads.txt                 # AdSense verification
├── vercel.json             # Vercel deployment config
└── *-nepal.html            # 37 article pages
```

---

## Deploy to Vercel

### Option 1: GitHub → Vercel (recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import the GitHub repo
4. Project name: `skincareguide-skg`
5. Click **Deploy**

### Option 2: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 3: Drag-and-drop
1. Vercel dashboard → New Project → drag the project folder

---

## Add to Google AdSense

1. **AdSense Dashboard → Sites → Add Site:** `skincareguide-skg.vercel.app`
2. **Google Search Console:** add property → submit `sitemap.xml`
3. **Wait 4–6 weeks** for indexing
4. **Request review** in AdSense
5. **After approval:** enable Auto Ads → Vignette ads for Google's compliant interstitial system

---

## Customisation

Before deploying:
1. Replace `G-XXXXXXXXXX` placeholder GA4 ID in all HTML files with your real Measurement ID
2. Verify `ads.txt` matches your AdSense pub ID

---

## License

© 2026 Thunder Anuprayog. All article content is original. Code under MIT.
