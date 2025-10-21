# Fortunes (Jump Version) — English UI

- `index.html`: Enter number (1–50) to jump to `fortuneX.html`.
- `fortune1.html` … `fortune50.html`: Each fortune on its own page (includes a back-to-index button).
- `qr_all.html`: In-browser QR generator. It auto-detects the deployed base URL and builds QR codes for:
  - Direct ID links: `index.html?id=1..50`
  - Individual pages: `fortune1.html..fortune50.html`

## Deploy via GitHub Pages
1. Create a **public** repository (e.g., `fortunes`).
2. Upload all files to the repository root.
3. Go to **Settings → Pages**:  
   - Build and deployment: **Deploy from a branch**  
   - Branch: `main`, Folder: `/ (root)` → Save
4. Your site will be at: `https://<username>.github.io/<repo>/index.html`

## Without Pages (temporary access)
1. Open `index.html` in the repo and click **Raw** to copy the raw link.
2. Go to https://raw.githack.com/ and paste the raw link to get a public URL.
3. Repeat for `qr_all.html` if needed.

## Notes
- All page text is English-only.
- Fortune texts were reviewed: no discriminatory or sensitive wording.
