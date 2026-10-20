# FremontTrader website and public app pages

The FremontTrader company homepage, public logo resources, and documentation for Bandwidth Meter and TV Checkup. This repository contains public website content, artwork, privacy policy, terms of use, and the original TV Checkup sound samples intended for public playback. App source, internal knowledge, distribution archives, credentials, and signing files belong elsewhere.

- Company: https://fremonttrader.com/ and https://fremonttrader.github.io/
- Logo resources: https://fremonttrader.com/resources/ and https://fremonttrader.github.io/resources/
- Bandwidth Meter: https://fremonttrader.github.io/bandwidth-meter/
- Bandwidth Meter privacy: https://fremonttrader.github.io/bandwidth-meter/privacy/
- Bandwidth Meter terms: https://fremonttrader.github.io/bandwidth-meter/terms/
- TV Checkup: https://fremonttrader.github.io/tv-checkup/
- TV Checkup privacy: https://fremonttrader.github.io/tv-checkup/privacy/
- TV Checkup terms: https://fremonttrader.github.io/tv-checkup/terms/

GitHub Pages publishes the root of `main`. Static HTML and CSS; no build, third-party scripts, external font requests, or analytics are required. The company homepage uses the approved icon-left FT monogram and a self-hosted Space Grotesk font under the included SIL Open Font License. The existing app pages retain their own artwork and print styling. Preview with `python3 -m http.server --bind 127.0.0.1 8766`.

Cloudflare's `fremonttrader-github-proxy` Worker serves the GitHub Pages content through `fremonttrader.com`. Keep GitHub Pages' custom domain unset and do not add a root `CNAME` file: both hostnames must continue serving the site directly, including the existing `/bandwidth-meter/privacy/` and `/bandwidth-meter/terms/` paths.

Keep disclosures synchronized with app behavior. Bandwidth Meter retains this repository’s public Issues tracker as its policy contact; those requests are public. TV Checkup uses the publisher-supplied support@fremonttrader.com address. Do not substitute a private or work email. Preserve the distinction between device-local information, email support, website request logs, and independent Roku platform practices. Bandwidth Meter’s terms preserve its MIT license rights; TV Checkup’s original software and assets are all rights reserved, with permission to use the distributed app and preservation of applicable third-party rights.

## App branding

The website uses the actual Bandwidth Meter Roku artwork, copied byte-for-byte: `assets/bandwidth-meter-globe.png` from the app’s `images/splash_globe.png` for the shared header and favicon, and `assets/bandwidth-meter-app-icon.png` from `images/icon_focus_fhd.png` for the homepage. Preserve their aspect ratios and original artwork; do not replace them with a generated logo or generic initials.

Keep the header globe at 40px wide and the homepage icon at 120px (96px on small screens). HTML width/height attributes must use compact display sizes so missing or cached CSS cannot expose the full-resolution image size. Update the stylesheet version query when changing branding styles.

## TV Checkup pages

Added October 19, 2026 for app version 1.0.15. The three pages reuse the Bandwidth Meter HTML structure, class names, navigation, responsive layout, and unchanged `assets/styles.css?v=20260928-compact-logo`. `assets/tv-checkup-app-icon.png` is a byte-for-byte copy of TV Checkup’s original 540×405 `images/icon_focus_fhd.png`; display dimensions preserve its aspect ratio.

The privacy policy covers local device readings, ten on-device observation choices, optional email support, GitHub Pages, and Cloudflare when visitors use the custom domain. The prepared 1.0.16 page updates disclose selected Sound Checks samples played over HTTPS directly from GitHub Pages. They distinguish this upcoming behavior from fully bundled 1.0.15. Keep version language synchronized with the actual release. There is no app-managed sound cache or promised offline playback for the hosted library. Keep deletion instructions aligned with My checkup → Options (*) → Clear all. App features and limits are based on the current runtime; these pages do not certify Store approval or hardware accuracy.
