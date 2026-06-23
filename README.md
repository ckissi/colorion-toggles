# CSS Toggle Library

A library of **30 pure-CSS toggles** — switches, checkboxes and radios — with no JavaScript and no dependencies. Click any toggle to view and copy its self-contained CSS, or grab a ready-made prompt to have your coding agent recreate it.

🔗 **Live site:** [toggles.colorion.co](https://toggles.colorion.co)

## Features

- **Pure CSS** — every toggle is driven entirely by a native `<input>` and the `:checked` pseudo-class. No JavaScript required to use them.
- **Self-contained snippets** — each copyable snippet ships its own theme tokens and base styles, so it works standalone wherever you paste it.
- **Themeable** — colors are exposed as CSS custom properties (`--primary`, `--secondary`, `--surface`); override them to recolor any toggle.
- **Accessible** — visible focus states and `prefers-reduced-motion` support built in.
- **Copy as CSS or as a prompt** — grab the raw CSS, or a self-contained LLM prompt that recreates the toggle exactly.

## Contents

| Family | Count |
| --- | --- |
| Switches / toggles | 16 |
| Checkboxes | 8 |
| Radios (toggleable) | 6 |

## Getting started

This is an [Astro](https://astro.build) site.

```bash
# Install dependencies
npm install

# Start the dev server (http://localhost:4321)
npm run dev

# Build for production (outputs to ./dist)
npm run build

# Preview the production build
npm run preview
```

## Project structure

```
src/
  layouts/Layout.astro    # Base HTML shell
  pages/index.astro       # The toggle library (markup, styles, snippets)
  styles/global.css       # Global styles
public/                   # Static assets (fonts, images)
```

All toggle definitions live in [`src/pages/index.astro`](src/pages/index.astro) — each entry declares its base family styles and a small set of variation rules.

## Using a toggle

1. Open the [live site](https://toggles.colorion.co).
2. Click a toggle to flip it, or use the **CSS** / **Prompt** buttons on each cell.
3. Copy the snippet — it's fully self-contained and ready to paste into your project.

## Hosting

Hosted on [Sevalla](https://sevalla.com).

## Part of the Colorion network

This is one of several free tools by [Colorion](https://colorion.co):
[2 Color Combinations](https://2colors.colorion.co) ·
[Color Palettes](https://colorpalettes.colorion.co) ·
[Palette Generator](https://palettegenerator.colorion.co) ·
[Gradient Buttons](https://gradientbuttons.colorion.co) ·
[Animated Buttons](https://animatedbuttons.colorion.co) ·
[CSS Loaders](https://cssloaders.colorion.co)

## License

MIT © [Csaba Kissi](https://github.com/ckissi)
