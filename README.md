# Vivliostyle Theme Vivliostyle Thesis

[![npm: version](https://flat.badgen.net/npm/v/vivliostyle-theme-thesis)](https://npmjs.com/package/vivliostyle-theme-thesis)
[![npm: total downloads](https://flat.badgen.net/npm/dt/vivliostyle-theme-thesis)](https://npmjs.com/package/vivliostyle-theme-thesis)
![npm: license](https://flat.badgen.net/npm/license/vivliostyle-theme-thesis)

Academic theme (thesis)

## Install

```bash
npm install --save vivliostyle-theme-thesis
# or
yarn add vivliostyle-theme-thesis
```

## Use

In `vivliostyle.config.js`:

```js
module.exports = {
  theme: 'vivliostyle-theme-thesis',
};
```

## Dev

Run `vivliostyle-theme-scripts preview` to preview your `theme.css`.

```bash
vivliostyle-theme-scripts preview theme.css
```

You can specify layout file with `--layout` flag:

```bash
vivliostyle-theme-scripts preview theme.css --layout example/default.md
```

Run `vivliostyle-theme-scripts validate` before publishing your package.

```bash
vivliostyle-theme-scripts validate
```
