# FremontTrader brand resources

This folder preserves all seven logo previews and contains the assets used by the minimal company homepage. Open `index.html` to browse the preview archive; each image links to its original PNG.

## Original logo previews

The files below are byte-for-byte copies of the generated originals. Each PNG is **1536 × 1024 pixels**, preserved without resizing or compression changes.

| File in `logos/` | Preview | Font direction |
| --- | --- | --- |
| `fremonttrader-01-shared-stem.png` | 01 — Shared stem | Outfit SemiBold |
| `fremonttrader-02-interlock.png` | 02 — Interlock | Manrope Bold |
| `fremonttrader-03-compact-frame.png` | 03 — Compact frame | Sora SemiBold |
| `fremonttrader-04-soft-line.png` | 04 — Soft line | Plus Jakarta Sans SemiBold |
| `fremonttrader-05-negative-space.png` | 05 — Negative space | Space Grotesk Medium |
| `fremonttrader-06-forward-lean.png` | 06 — Forward lean | Montserrat SemiBold |
| `fremonttrader-05-horizontal.png` | 05 — Approved horizontal layout | Space Grotesk Medium |

Font labels on these generated previews describe the **proposed font direction**. They do not establish that the image generator rendered the exact named font.

## Homepage assets

`logos/fremonttrader-monogram.svg` is a clean vector reconstruction based on the approved horizontal raster preview. It preserves the chosen symbol's geometric structure and negative spaces; it is **not an exact pixel trace**. The SVG scales cleanly for website use.

The homepage renders the company name as actual text using self-hosted **Space Grotesk at weight 500**. The font file is `fonts/SpaceGrotesk-Variable.ttf`, an unmodified variable font from the official Google Fonts repository. It supports normal-style weights 300–700. Serving it from this repository avoids a third-party font request.

- [Official font directory](https://github.com/google/fonts/tree/main/ofl/spacegrotesk)
- [Original font download](https://raw.githubusercontent.com/google/fonts/main/ofl/spacegrotesk/SpaceGrotesk%5Bwght%5D.ttf)
- [Official font metadata](https://raw.githubusercontent.com/google/fonts/main/ofl/spacegrotesk/METADATA.pb)
- [Original license](https://raw.githubusercontent.com/google/fonts/main/ofl/spacegrotesk/OFL.txt)

Space Grotesk is copyright 2020 The Space Grotesk Project Authors and is distributed under the **SIL Open Font License 1.1**. The complete notice and license are preserved in `fonts/OFL.txt`; keep that file with the font when redistributing it.

The gallery uses static HTML and CSS with no JavaScript. These company branding resources do not replace Bandwidth Meter's existing Roku artwork, app pages, privacy policy, or terms.
