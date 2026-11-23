# SCOPX.I.E Mobile PWA (Demo)

Arabic-first, responsive demo workspace for Android phones and desktop browsers. Uses **synthetic demo data only**.

> Not a clinical product. Do not enter real patient information, clinical notes, or real endoscopy images.

## Try locally
- Python 3: `python -m http.server 8000`
- Open `http://localhost:8000` in Chrome/Edge.
- On Android Chrome, use **Install app** or **Add to Home screen**. PWA install requires HTTPS or localhost.

## Publish on GitHub Pages
1. Create a new GitHub repository (suggested name: `scopx-mobile-demo`).
2. Upload the contents of this repository to the root of your GitHub repo (not the enclosing ZIP folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **GitHub Actions** as source.
5. The included workflow deploys the site automatically when you push to `main`.
6. Wait for the Pages workflow to complete; your live URL will appear under Settings → Pages.

## Demo functions
- Dashboard and synthetic patients
- Add/search demo patients
- Create, start, and complete procedures
- Demo report drafting/status
- Attach/remove demo images to procedures
- JSON export/import
- Responsive layout and service-worker cache

## Privacy / storage
The demo stores its dataset in browser localStorage. It is device/browser-local and not a secure medical record system. Backup JSON includes all local demo data.
