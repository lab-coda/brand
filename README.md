# CODA Lab brand

Logo files for CODA Lab (Cognition · Open Data · Analysis), Department of Psychiatry, University of British Columbia.

For the figure style and fonts, see [lab-coda/coda-style](https://github.com/lab-coda/coda-style).

## Using the logo

You're welcome to use these files to refer to CODA Lab, for example in talks, posters, papers, and collaborators' websites. Please don't modify them, use them for other projects, or use them in a way that suggests CODA Lab endorses something it doesn't. The files are not under an open licence; all rights are reserved by CODA Lab. Questions: contact the lab through [lab-coda.github.io](https://lab-coda.github.io/).

## Files

```
logo/
  svg/   coda_wordmark_*.svg   wordmark, text outlined (no font needed)
         coda_lockup_*.svg     wordmark + tagline
         coda_avatar_*.svg     c_ square mark
  png/   1200 px-wide wordmarks and lockups; avatars at 512/256/180/64/32 px
  favicon.ico                  16/32/48 px
github/  coda_github-banner_{light,dark}.svg/.png   wide banner for the org profile page
         org-profile-README.md                      ready-to-use org profile README
```

| You need | Use |
|---|---|
| Logo on a light background | `coda_wordmark_on-light` |
| Logo on a dark background | `coda_wordmark_on-dark` |
| One colour only (single-colour print, busy photos) | `coda_wordmark_one-colour-ink` / `-white` |
| Website header, poster, first slide of a talk | `coda_lockup_on-light` / `-on-dark` |
| GitHub org, social profiles | `coda_avatar_square_512.png` |
| GitHub org profile page banner | `github/coda_github-banner_light` / `_dark` |
| Slack/Teams icon | `coda_avatar_rounded_*` |

Use SVG wherever the tool accepts it (web, Inkscape, Illustrator, Keynote) and PNG elsewhere (PowerPoint, Google Slides).

## Colours

| Role | Hex | Use |
|---|---|---|
| Ink | `#141B2D` | Text, dark backgrounds |
| Magenta | `#BE185D` | Accent on light backgrounds (fine for small text) |
| Pink | `#F472B6` | Accent on dark backgrounds only |
| Slate | `#4A5263` | Secondary text |
| Mist | `#B8BEC9` | Secondary text on dark |

## Rules

- Keep clear space around the wordmark at least the height of the letter **c**.
- Minimum width: 80 px on screen, 20 mm in print. Below that, use the `c_` avatar.
- Don't recolour, stretch, add effects to, or retype the wordmark.
- Next to the UBC logo, keep the two separate with clear space between them, and follow UBC's brand guidelines for co-branded material.

## Type

Inter for all text (slides, posters, figures, website); Fira Code for code. Both are free under the SIL Open Font License and bundled in `coda-style`.

## Website favicon

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/coda_avatar_rounded.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/coda_avatar_square_180.png">
```
