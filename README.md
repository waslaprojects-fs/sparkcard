# Spark Math Center – Digital Business Card

A simple, single-file digital business card that works in any browser.

## Setup

1. **Phone & WhatsApp**  
   Edit `index.html` and replace `1234567890` in the WhatsApp link with your full number **with country code, no + or spaces**:
   - `https://wa.me/1234567890` → e.g. `https://wa.me/966501234567` for Saudi Arabia.

2. **Facebook**  
   Replace `https://www.facebook.com/YourPage` with your Facebook page URL.

3. **Instagram**  
   Replace `https://www.instagram.com/YourProfile` with your Instagram profile URL, and update the label `@yourprofile` if you want.

4. **Website**  
   Replace `https://www.yourmathcenter.com` with your real business website.

## Run locally

Open `index.html` in a browser, or use a local server:

```bash
# Python 3
python3 -m http.server 8080

# or npx
npx serve .
```

Then visit `http://localhost:8080` (or the port shown).

## Deploy

Upload the whole folder (including `assets/spark-logo.png`) to any static host (GitHub Pages, Netlify, Vercel, or your own server) to share the card online.
# sparkcard
