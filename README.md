# mkdir

A filesystem-flavored theme for [micro.blog](https://micro.blog/).

Serif body (De Gruyter Serif), monospace metadata (JetBrains Mono), single column, ASCII-tree archive, terminal-prompt footer, light/dark/auto toggle. Designed for thoughtful long-form essays mixed with short status posts.

## Install on micro.blog

1. Go to **Design → Plug-ins** in your micro.blog account.
2. Click **Install from GitHub** and enter `charlescisco/mkdir`.
3. Activate the plug-in. micro.blog auto-merges [`theme-blank`](https://github.com/microdotblog/theme-blank) underneath, so feeds, sitemap, and the photos page work out of the box.

## Local development

Requires Hugo extended (≥ 0.128).

```sh
cd exampleSite
hugo server --themesDir ../.. --theme mkdir
```

Then open http://localhost:1313.

## Customization

Light/dark colors, type scale, and spacing are CSS custom properties in `assets/css/tokens.css`. The terminal prompt in the footer uses your blog's `params.author.username` and a short host derived from the site URL.

## License

MIT. Bundled fonts ship under their respective OFL 1.1 licenses (see `static/fonts/`).
