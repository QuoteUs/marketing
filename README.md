# QuoteUs marketing

Brand assets and marketing material for [QuoteUs](https://quoteus.eu), the
quote book for your student house, friend group or family.

## Contents

| Path | What's in it |
| --- | --- |
| `brand/logos/` | Mark and wordmark as `svg/`, `png/` (128–2048 px), `webp/`, `jpg/` and `ico/` |
| `brand/app-icon/` | App icon (light, dark, blush) at 1024 px plus iOS sizes |
| `fonts/` | Newsreader (TTF + WOFF2) and its OFL license |
| `BRAND.md` | Colours, typography, logo rules, tone of voice |
| `social/`, `press-kit/`, `copy/`, `screenshots/` | Placeholders for upcoming material |

## Logo quick pick

- Light background → `*-oxblood`; dark background → `*-blush`; single-colour print → `quoteus-mark-ink`.
- Prefer SVG. Use PNG/WebP when a platform needs raster; JPG files have a solid background.
- Filenames: `quoteus-{mark|wordmark}-{colour}[-{width}].{ext}`.

## Regenerating raster logos

The SVGs in `brand/logos/svg/` are the source of truth (copied from the website's
`public/logos`). PNG/WebP/JPG/ICO exports are generated from them; if a logo
changes, update the SVGs and re-export all formats.

## Usage

Proprietary, see [LICENSE.md](LICENSE.md). Follow [BRAND.md](BRAND.md).
