# CASEVAC marketing site

Static site for CASEVAC: Nearest Trauma Center. Prepared for GitHub Pages at https://casevac.app/.

## Pages

- `index.html` — marketing home (hero, features, Free vs Pro, privacy, FAQ, 911 disclaimer)
- `privacy.html` — privacy policy, written to match the app’s current code
- `terms.html` — terms of use, Apple standard EULA, subscription auto-renew terms
- `support.html` — support page

## Local preview

Open `index.html` in a browser, or from this folder:

```
python3 -m http.server 8080
```

Then visit http://localhost:8080

## TODOs before going public

1. **Support email.** Legal and support pages now use `support@casevac.app`. Confirm the inbox is live before treating it as a public contact address.
2. **App Store URL.** The “Coming soon to the App Store” badge is not a link. After the app is live, turn it into a real App Store link. Do not use a placeholder URL.
3. **Device screenshots.** This draft uses the app icon only, not product shots. When build 23 screenshots are in hand, add captioned iPhone and iPad images to the hero or a gallery.
4. **Seller name.** Legal pages name Mark Iglar as an individual developer. Update to the LLC name after the Texas LLC is formed and Apple’s seller name is changed.
5. **ProConfig URLs.** The app still points Terms and Privacy at `https://jethrohudson.github.io/casevac-legal`. Point `ProConfig.legalBaseURL` at this site once it is hosted.
6. **Search indexing.** Done at launch: `robots.txt` allows all, `sitemap.xml` lists the public pages, and the `noindex, nofollow` meta tags have been removed.
7. **This is not legal advice.** Have a lawyer review privacy.html and terms.html before App Store submission.

Prices are written as “See App Store” because pricing is not final.
