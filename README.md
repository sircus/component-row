# sircus-components-grid

[![npm version](https://img.shields.io/npm/v/sircus-components-grid.svg?style=flat)](https://www.npmjs.com/package/sircus-components-grid)

## Dependencies
- [sircus-global-property](https://github.com/sircus/global-property)


## Installation

> npm:

```bash
$ npm install sircus-components-grid sircus-global-property
```

## Usage

> cssnext:

input.css
```css
@import "sircus-components-grid";
@import "sircus-global-property";
```

> sass:

input.scss
```scss
@import "node_modules/sircus-global-property/converted";
@import "node_modules/sircus-components-grid/converted";
```


> html

```html
<div class="Grid">
  <div class="Grid-col t-width1of2"></div>
  <div class="Grid-col t-width1of2"></div>
</div>

<div class="Grid Grid--center">
  <div class="Grid-col t-width1of2"></div>
  <div class="Grid-col t-width1of2"></div>
</div>

<div class="Grid Grid--right">
  <div class="Grid-col t-width1of2"></div>
  <div class="Grid-col t-width1of2"></div>
</div>

<div class="Grid Grid--left">
  <div class="Grid-col t-width1of2"></div>
  <div class="Grid-col t-width1of2"></div>
</div>

<div class="Grid Grid--top">
  <div class="Grid-col t-width1of2"></div>
  <div class="Grid-col t-width1of2"></div>
</div>

<div class="Grid Grid--middle">
  <div class="Grid-col t-width1of2"></div>
  <div class="Grid-col t-width1of2"></div>
</div>

<div class="Grid Grid--bottom">
  <div class="Grid-col t-width1of2"></div>
  <div class="Grid-col t-width1of2"></div>
</div>

```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
