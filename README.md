# stylelint-config-mass

[![Author](https://img.shields.io/badge/author-sabertaz-lightgrey?style=for-the-badge)](https://github.com/sabertazimi)
[![LICENSE](https://img.shields.io/github/license/sabertazimi/stylelint-config-mass?style=for-the-badge)](https://raw.githubusercontent.com/sabertazimi/stylelint-config-mass/master/LICENSE)

[![Code Lines](https://img.shields.io/tokei/lines/github/sabertazimi/stylelint-config-mass?style=for-the-badge&logo=visualstudiocode)](https://github.com/sabertazimi/stylelint-config-mass)
[![Code Size](https://img.shields.io/github/languages/code-size/sabertazimi/stylelint-config-mass?logo=visualstudiocode&style=for-the-badge)](https://github.com/sabertazimi/stylelint-config-mass)

A stylelint config based on `stylelint-config-sass-guidelines` for mass.css

## Installation

```bash
npm install -D stylelint-config-mass
```

## Usage

set `.stylelintrc.json` to:

```json
{
  "extends": "stylelint-config-mass"
}
```

### Extending the config

Simply add a "rules" key to your config and add your overrides there.

For example, to change the indentation to tabs and turn off the number-leading-zero rule:

```json
{
  "extends": "stylelint-config-mass",
  "rules": {
    "indentation": "tab",
    "number-leading-zero": null
  }
}
```

## Highlight

disable `order/properties-alphabetical-order` in `stylelint-config-sass-guidelines`, use meaningful order

```json
{
  "rules": {
    // ...
    "order/properties-order": [
      "position",
      "z-index",
      "top",
      "right",
      "bottom",
      "left",
      "box-sizing",
      "display",
      "visibility",
      "float",
      "clear",
      "width",
      "min-width",
      "max-width",
      "height",
      "min-height",
      "max-height",
      "overflow",
      "margin",
      "margin-top",
      "margin-right",
      "margin-bottom",
      "margin-left",
      "padding",
      "padding-top",
      "padding-right",
      "padding-bottom",
      "padding-left",
      "border",
      "border-width",
      "border-top-width",
      "border-right-width",
      "border-bottom-width",
      "border-left-width",
      "border-style",
      "border-top-style",
      "border-right-style",
      "border-bottom-style",
      "border-left-style",
      "border-color",
      "border-top-color",
      "border-right-color",
      "border-bottom-color",
      "border-left-color",
      "outline",
      "list-style",
      "table-layout",
      "caption-side",
      "border-collapse",
      "border-spacing",
      "empty-cells",
      "background",
      "background-color",
      "background-image",
      "background-repeat",
      "background-position",
      "color",
      "font",
      "font-family",
      "font-size",
      "font-weight",
      "line-height",
      "text-align",
      "text-indent",
      "text-transform",
      "text-decoration",
      "letter-spacing",
      "word-spacing",
      "white-space",
      "vertical-align",
      "opacity",
      "cursor",
      "content",
      "quotes"
    ],
    // ...
  }
}
```

## Reference

- [Sass Guidelines](https://github.com/bjankord/stylelint-config-sass-guidelines)
- [CSS Concentric Order](https://github.com/chaucerbao/stylelint-config-concentric-order)

## Contact

[![Email](https://img.shields.io/badge/-Gmail-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sabertazimi@gmail.com)
[![Twitter](https://img.shields.io/badge/-Twitter-1da1f2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/sabertazimi)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sabertazimi)
