# Cata breakpoints

[![Build Status](https://travis-ci.org/raulghm/cata-breakpoints.svg?branch=master)](https://travis-ci.org/raulghm/cata-breakpoints)

## Custom media queries

These are predefined values and recommendations based on this article
http://bradfrost.com/blog/post/7-habits-of-highly-effective-media-queries
I prefer em instead of px, and I recommend applying a subset of values
depending on the type of project and personal preferences.

```css
@custom-media --sm-viewport (min-width: 24em);
@custom-media --md-viewport (min-width: 46.8em);
@custom-media --lg-viewport (min-width: 50em);
@custom-media --xl-viewport (min-width: 60em);
```

## How use

```css
@media (--sm-viewport) {
  div {
    width: 200px;
  }
}
```

## Installation

## NPM
```
npm install cata-breakpoints
```

## Yarn
```
yarn add cata-breakpoints
```

## Download
[Download](https://github.com/raulghm/cata-breakpoints/releases)

## Testing

Install [Node](http://nodejs.org) (comes with npm) and run:

```
npm install
```

Or install [Yarn](https://yarnpkg.com/en/docs/install) and run:

```
yarn
```

To generate a build:

```
npm run build
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](http://stylelint.io/)

```
npm run lint
```

To generate the testing build.

```
npm run build-test
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome
* Firefox
* Safari
* Opera
* Internet Explorer 9+
