# devins-badges-plus

A small, focused extension of [Devin's Badges](https://github.com/intergrav/devins-badges), currently containing the `cozy/license` badge set as SVG assets.

![](assets/cozy/license/cc0_vector.svg)

> ## Disclaimer (from upstream context)
>
> As of Jan 16, 2026, upstream only accepts badges for very notable projects into the official repository. You can still use the badge template and host/distribute your own badges.
>
> Upstream also notes that PRs may be hard to merge there because the Figma source file is binary-heavy and needs manual organization.
>
> This repository exists as an independent, lightweight place for additional badge assets.

## About

This repository is meant to be practical and easy to reuse:

- Keep badge assets in plain SVG files.
- Keep naming predictable.
- Keep licensing clear and permissive.

## Repository contents

```text
assets/
  cozy/
    license/
      agpl-v3_vector.svg
      arr_vector.svg
      cc-by-4.0_vector.svg
      cc-by-nc-4.0_vector.svg
      cc-by-nc-nd 4.0_vector.svg
      cc-by-nc-sa 4.0_vector.svg
      cc-by-nd-4.0_vector.svg
      cc-by-sa-4.0_vector.svg
      cc0_vector.svg
      gpl-v3_vector.svg
      lgpl-v3_vector.svg
      mit_vector.svg
```

## Using in your project

Pick the SVG you need from `assets/cozy/license/` and use it directly.

Examples:

```html
<img alt="MIT License" src="assets/cozy/license/mit_vector.svg" />
```

```markdown
![MIT License](assets/cozy/license/mit_vector.svg)
```

If you publish these files from your own CDN or static host, replace the path with your hosted URL.

## Adding more badges

- Open an issue with the badge idea and expected label text.
- Open a PR with new SVG files if you already have a design.
- Keep filenames consistent with the existing `*_vector.svg` pattern.

## Credits

- Original project: [intergrav/devins-badges](https://github.com/intergrav/devins-badges)
- Original creator: [intergrav](https://devins.page)

For upstream badge references and broader catalog docs, see:

- https://intergrav.github.io/devins-badges-docs/badges/
- https://intergrav.github.io/devins-badges-docs/credits/

## License

This repository is licensed under **CC0 1.0** (see `LICENSE`).

In short: you can use and modify these badge designs for almost any purpose, including commercial use, with no attribution required.

Attribution is still appreciated when practical.

