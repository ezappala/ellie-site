# Ellie's personal site

_Made With Chiri 🌸_

Find a live version at [maybeellie.dev](https://maybeellie.dev)
Locate the template via [astro-chiri](https://github.com/the3ash/astro-chiri)

## Features

- [x] Build with Astro
- [x] Responsive
- [x] Light / Dark mode
- [x] MDX
- [x] KaTeX
- [x] Sitemap
- [x] OpenGraph
- [x] RSS

## Local hosting

If you'd like to run and host this repo locally, for whatever reason:

1. Run the following commands:

   ```bash
   git clone git@github.com:ezappala/ellie-site

   cd ellie-site

   bun install

   bun dev
   ```

2. Use `bun new <title>` to create new posts, or add a posts to `src/content/posts`.

3. Build with `bun build` and deploy the generated `dist/` directory to any static hosting platform. Link Card metadata is fetched automatically during `pnpm dev` and `pnpm build` and stored in `src/data/link-card-metadata.json` so cards render as static HTML.

## Commands

- `bun new <title>` - Create a new post; use `_title` for drafts
- `bun update-link-metadata` - Refresh metadata for `::link` cards' use `--force` to re-fetch existing entries
- `bun update-theme` - Update the theme to the most recently updated version

## References

- https://paco.me/
- https://benji.org/
- https://shud.in/
- https://retypeset.radishzz.cc/

## Licenses

Template: MIT https://github.com/the3ash

Personal additions to the code: MIT [https://github.com/ezappala/](./LICENCE)

Content of this website: CC-BY
