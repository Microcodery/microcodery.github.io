# Brand assets

Supplied source files. The page does not load them at runtime — `../favicon.svg`,
`../icon-512.png`, `../og-image.png`, and the inline hero mark in `../../index.html`
are all derived from `mark.svg`. Change `mark.svg` and those four need redoing.

| File | What it is |
| --- | --- |
| `mark.svg` | The mark, `fill="currentColor"` so it follows whatever colour it inherits. The canonical source. |
| `mark-black.svg`, `mark-white.svg` | Same geometry with the fill hardcoded, for contexts that can't inherit a colour. |
| `mark-small.svg` | Outer silhouette only, no slots. Unused — at 16px the full mark still reads as an M, while this reduces to a plain square. |
| `lockup-black.svg`, `lockup-white.svg` | **Unfinished, do not ship.** The wordmark is an SVG `<text>` element with a placeholder `font-family`, so it renders differently wherever the font is missing, and the viewBox has to be re-measured by hand after any font change. It also reads "Microcodery" while the site now says "The Microcodery". |
