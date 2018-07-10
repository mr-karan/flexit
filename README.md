# [Flexit](https://mrkaran.com/flexit/)

Flexit is a **lightweight CSS Grid** based on [Flexbox](https://www.w3.org/TR/css-flexbox-1/#intro).

[![npm](https://img.shields.io/npm/v/flexitgrid.svg)][npm-link]
[![npm](https://img.shields.io/npm/dm/flexitgrid.svg)][npm-link]

<a href="https://mrkaran.com/flexit/"><img src="https://raw.githubusercontent.com/mr-karan/flexit/master/static/images/logo.png" alt="Flexit: Responsive CSS Grid" style="max-width:100%;" width="200"></a>

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

### CDN

[https://cdnjs.com/libraries/flexit](https://cdnjs.com/libraries/flexit)


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

## Demo

[Visit](https://mrkaran.com/flexit/) the demo page built entirely using Flexit.


## Copyright and license

Code copyright 2018 Karan Sharma. Code released under [the MIT license](https://github.com/mr-karan/flexit/blob/master/LICENSE).

[npm-link]: https://www.npmjs.com/package/flexit
