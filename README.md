# [Flexit](https://mrkaran.com/flexit/)
![Logo](static/images/logo.png "Flexit")

Flexit is a **lightweight CSS Grid** based on [Flexbox](https://www.w3.org/TR/css-flexbox-1/#intro).

[![npm](https://img.shields.io/npm/v/flexitgrid.svg)][npm-link]
[![npm](https://img.shields.io/npm/dm/flexitgrid.svg)][npm-link]

## Demo

[Visit](https://mrkaran.com/flexit/) the demo page built entirely using Flexit.


## Quick install

Flexit is in active development:

### NPM

```sh
npm install flexitgrid
```

**or**

### Yarn

```sh
yarn add flexitgrid
```

### Import
After installation, you can import the CSS file into your project using this snippet:

```sh
import 'flexit/dist/flexit.css'
```

### Manual Method

You can download the CSS file from [here](https://github.com/mr-karan/flexit/blob/master/dist/flexit.css) and use it in your HTML as
```html
<link rel="stylesheet" href="flexit.css">
```


## Clean Syntax

Flexit has simple, human readable classes for naming rows and columns. The class names are intuitive while laying out a grid. For example to
have 2 columns occupying 50% of the grid and one column occupying the remaining grid, the HTML would look like:

```html
<div class="row">
    <div class="three columns">
        <p>Content</p>
    </div>
    <div class="three columns">
        <p>Content</p>
    </div>
    <div class="six columns">
        <p>Content</p>
    </div>
</div>
```


## Copyright and license

Code copyright 2018 Karan Sharma. Code released under [the MIT license](https://github.com/mr-karan/flexit/blob/master/LICENSE).

[npm-link]: https://www.npmjs.com/package/flexitgrid
