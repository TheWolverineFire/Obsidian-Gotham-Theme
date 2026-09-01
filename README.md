# Gotham

A monochrome art deco theme for [Obsidian](https://obsidian.md) — black, white, and silver only, no gold. Geometric ornament (chevron dividers, chamfered corners, a sunburst-topped infobox) carries the personality instead of color.

![Gotham theme screenshot](./screenshots/screenshot.png)

## Features

- **True monochrome palette** — light and dark variants built from pure grayscale, no accent hue anywhere in the interface.
- **Chevron dividers** on H1 and H2 headings, built from stacked CSS gradients — no images.
- **Chamfered geometry** throughout: tabs, callouts, and blockquotes all use clipped corners instead of rounded ones, echoing a stepped skyscraper silhouette.
- **Deco typography** — [Poiret One](https://fonts.google.com/specimen/Poiret+One) for headings and body text, with [Cinzel Decorative](https://fonts.google.com/specimen/Cinzel+Decorative) available as an ornamental accent font.
- **Diamond list bullets** and a deco-styled frontmatter panel.
- Fully themed light and dark modes.

## Installation

### From Obsidian (once published)

1. Open **Settings → Appearance → Themes → Manage**.
2. Search for "Gotham".
3. Click **Install and use**.

### Manually

1. Download `manifest.json` and `theme.css` from the [latest release](../../releases/latest).
2. Create a folder named `Gotham` inside your vault's `.obsidian/themes/` directory.
3. Place both files inside it.
4. In Obsidian, go to **Settings → Appearance → Themes**, and select **Gotham**.

## Fonts

Gotham references the following fonts by name but does not bundle them. Install them from [Google Fonts](https://fonts.google.com) for the intended look — the theme falls back to system fonts if they're missing:

- **Poiret One** — headings and body text
- **Cinzel Decorative** — optional ornamental accent
- **JetBrains Mono** — code blocks

## Optional: the Wikibox snippet

This repository doesn't include it (community themes only support a single `theme.css`), but a companion CSS snippet — a floating infobox styled to match Gotham, with a chamfered double frame and sunburst-topped title — is available separately. Add it as a CSS snippet under **Settings → Appearance → CSS snippets** if you'd like it.

## License

MIT — see [LICENSE](./LICENSE).
