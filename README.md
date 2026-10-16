# Fuel Counter — Official Website & Legal Pages

This repository hosts the official landing page, legal documents (Privacy Policy, Terms of Service), and Google AdMob `app-ads.txt` authorization file for the **Fuel Counter** mobile app.

## Repository Contents

- `index.html` — Main app landing page (in English).
- `privacy-policy.html` — Privacy Policy page (insert your generated HTML inside the placeholder).
- `terms.html` — Terms & Conditions page (insert your generated HTML inside the placeholder).
- `app-ads.txt` — Google AdMob developer verification file (`google.com, pub-2577347291345423, DIRECT, f08c47fec0942fa0`).
- `.nojekyll` — Ensures GitHub Pages serves all static files and `app-ads.txt` directly without Jekyll filtering.
- `assets/` — Application icons, logos, and favicons.

---

## How to Publish to GitHub Pages

1. **Create a GitHub Repository:**
   - Go to [GitHub](https://github.com/new).
   - Create a new public repository (e.g. `fuel-counter-site` or `<your-username>.github.io`).

2. **Push this folder to GitHub:**
   ```bash
   cd C:\Users\Nikita\WebstormProjects\fuel-counter-site
   git init
   git add .
   git commit -m "feat: initial commit for Fuel Counter website and legal pages"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - In your GitHub repository, navigate to **Settings** ➔ **Pages**.
   - Under **Build and deployment** ➔ **Branch**: select `main` (root) and click **Save**.
   - Your site will be live at: `https://<your-username>.github.io/<repo-name>/` (or `https://<your-username>.github.io/` if using username repo).

---

## Linking in Google Play Console & AdMob

- **Website in Google Play Console:**
  Navigate to *Store presence* ➔ *Store settings* ➔ *Store listing contact details* ➔ *Website*, and enter your GitHub Pages URL:
  ```
  https://<your-username>.github.io/<repo-name>/
  ```

- **Privacy Policy in Google Play Console:**
  Navigate to *App content* ➔ *Privacy policy*, and enter:
  ```
  https://<your-username>.github.io/<repo-name>/privacy-policy.html
  ```

- **AdMob verification:**
  Google AdMob will automatically crawl `https://<your-username>.github.io/<repo-name>/app-ads.txt` and verify your app within 24 hours.
