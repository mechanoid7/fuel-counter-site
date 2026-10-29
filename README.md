# Fuel Counter — Official Website & Legal Pages

Official landing page, legal compliance documents (Privacy Policy, Terms of Service), and Google AdMob verification (`app-ads.txt`) for the **Fuel Counter** Android mobile application.

- **Live Website:** [https://fuel.nvos.com.ua/](https://fuel.nvos.com.ua/)
- **Google Play:** [Fuel Counter on Google Play](https://play.google.com/store/apps/details?id=com.nvos.fuelcounter)
- **Privacy Policy:** [https://fuel.nvos.com.ua/privacy-policy.html](https://fuel.nvos.com.ua/privacy-policy.html)
- **Terms of Service:** [https://fuel.nvos.com.ua/terms.html](https://fuel.nvos.com.ua/terms.html)
- **AdMob app-ads.txt:** [https://fuel.nvos.com.ua/app-ads.txt](https://fuel.nvos.com.ua/app-ads.txt)

---

## Google Play Console & AdMob Configuration

- **Website URL:**
  ```text
  https://fuel.nvos.com.ua/
  ```
  *(In Play Console: Store presence ➔ Store settings ➔ Store listing contact details ➔ Website)*

- **Privacy Policy URL:**
  ```text
  https://fuel.nvos.com.ua/privacy-policy.html
  ```
  *(In Play Console: Policy and programs ➔ App content ➔ Privacy policy)*

- **AdMob App-Ads.txt Verification:**
  ```text
  https://fuel.nvos.com.ua/app-ads.txt
  ```
  *(Google AdMob automatically crawls the app-ads.txt file using the developer website specified in the store listing)*

---

## Deployment

The website is deployed automatically via **GitHub Pages** from the root of the `main` branch:
[https://github.com/mechanoid7/fuel-counter-site](https://github.com/mechanoid7/fuel-counter-site)

To publish updates:
```bash
git add .
git commit -m "update site content and legal policies"
git push origin main
```
