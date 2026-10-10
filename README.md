# MyPR — website

Static, branded site for the MyPR iOS app: marketing landing, support, and privacy
policy, in **three languages** (Ukrainian, English, French). Hosted free on GitHub Pages.

## Structure

```
index.html / support.html / privacy.html      → Ukrainian (default, site root)
en/index.html / en/support.html / en/privacy.html → English
fr/index.html / fr/support.html / fr/privacy.html → French
styles.css                                     → shared styles
assets/                                         → beaver logo, localized hero banners, screenshots
```

Pure static HTML/CSS — no build step, no backend. A UA/EN/FR switcher sits in the header
of every page. Edit the `.html` files directly and `git push` to publish.

## Live URLs

- Home (UA): https://morozpavlo.github.io/mypr-site/
- Support (App Store Support URL): https://morozpavlo.github.io/mypr-site/support.html
- Privacy Policy: https://morozpavlo.github.io/mypr-site/privacy.html
- English: https://morozpavlo.github.io/mypr-site/en/
- French: https://morozpavlo.github.io/mypr-site/fr/

## Assets

Branded hero banners and screenshots are the App Store marketing images
(`header_*.png`, `01–04.png`), optimised to JPEG via `sips`. The logo is the app's
beaver mascot (`AppLogo`). Replace the images in `assets/` to refresh.
