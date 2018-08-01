# stylelint-config-mass

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