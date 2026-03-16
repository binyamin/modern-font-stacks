# Modern Font Stacks Module

Design tokens for Dan Klammer's
[Modern Font Stacks](https://github.com/system-fonts/modern-font-stacks).
Compatible with
[v2025.10 of the DTCG spec](https://www.designtokens.org/tr/2025.10/).

> [!IMPORTANT]
> This project requires little upkeep, but it _is_ maintained.

## Install

This module is intentionally not published to NPM. I may put it on JSR at some
point. You are welcome to install it using github specifiers, like so:

```sh
npm install binyamin/modern-font-stacks#semver:^0.1.0
```

## Usage

The default export is a standardized JSON file. You can consume it using tools
such as [sugarcube](https://sugarcube.sh/), [terrazzo](https://terrazzo.app/),
and [style dictionary](https://styledictionary.com/).

### Notes

All tokens are nested under the `"stack"` key. There is a vendor extension for
each token, using the key "`x-modern-font-stacks"`. The fields are:

- **group** (`null | "serif" | "sans" | "mono" | "cursive"`)
- **display** (`boolean`)

## Contributing

Issues are the way to go here. If something is out-of-date, let me know.

## Credits

All source-code is provided under the terms of
[the MIT license](https://github.com/binyamin/modern-font-stacks/blob/main/LICENSE).

The font-stacks, descriptions, and groupings are under
[the CC0 license](https://github.com/system-fonts/modern-font-stacks/blob/main/LICENSE).

Copyright 2025-2026 Binyamin Aron Green.
