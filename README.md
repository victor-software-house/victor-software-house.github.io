# victor-software-house.com

The Victor Software House website: one static page, served by GitHub Pages from `main`.

## Layout

- `index.html` holds the page and its styles.
- `404.html` is the page GitHub Pages serves for unknown paths.
- `logo.svg` and `logo-dark.svg` are the house mark on the cream and ink fields.
- `marks/` holds the ctl family marks, copied from each tool's `docs/`.
- `fonts/` holds Geist and Geist Mono (SIL Open Font License, see `fonts/OFL.txt`).
- `og.png` is the share image.
- `CNAME` binds the custom domain.

## Look

The palette, the mark grid and the type follow the ctl family
(`ctl-core/docs/brand.md`): cream `#f3efe6` and ink `#161616` trade field and figure,
rust `#c45c2a` is the one accent, and Geist Mono Black sets names.
Light and dark follow `prefers-color-scheme`.

The house mark is the torii from the GitHub org avatar, redrawn on the 32-unit grid with corner radius 6.
The beam is the rust part.

## Preview

Open `index.html` in a browser. Paths are relative, except in `404.html`, which needs the site root.

## Publish

Push to `main`. GitHub Pages deploys it to <https://victor-software-house.com>.
