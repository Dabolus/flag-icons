# &lt;flag-icons&gt;
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-unpublished-lightgrey.svg)](https://www.webcomponents.org/element/Dabolus/flag-icons)
[![Travis build](https://img.shields.io/travis/Dabolus/flag-icons.svg)](https://travis-ci.org/Dabolus/flag-icons)
[![GitHub release](https://img.shields.io/github/release/Dabolus/flag-icons/all.svg)](https://github.com/Dabolus/flag-icons)

_[Demo and API docs](https://www.webcomponents.org/element/Dabolus/flag-icons)_

`flag-icons` is an iconset that allows you to easily display flags
on you application/website.

It features 195 flat icons with rounded corners, that can be useful if you want to allow the user to change the language in you internationalized application.

_Note: the credits for the original flags go to [Muharrem Şenyıl](https://freebiesbug.com/psd-freebies/100-flat-flag-psd-icons/).<br>
I just ported them to SVG and then to an iconset._

## Installation
```
bower install --save Dabolus/flag-icons
```

## Usage
Using an iconset is extremely simple. These are the steps you need to follow:

1. Load the iconset:
   ```html
   <link rel="import" href="../bower_components/flag-icons/flag-icons.html">
   ```
2. Insert your icon using [`iron-icon`](https://www.webcomponents.org/element/PolymerElements/iron-icon)
   ```html
   <iron-icon icon="flag:gb"></iron-icon>
   ```
3. Done!

_The flags can also be used inside a [`paper-icon-button`](https://www.webcomponents.org/element/PolymerElements/paper-icon-button)._

Example with normal `iron-icon`s:
<!---
```html
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="flag-icons.html">
    <link rel="import" href="../iron-icon/iron-icon.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<iron-icon icon="flag:af"></iron-icon>
<iron-icon icon="flag:al"></iron-icon>
<iron-icon icon="flag:dz"></iron-icon>
```

Example with `paper-icon-button`s:
<!---
```html
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="flag-icons.html">
    <link rel="import" href="../iron-icon/iron-icon.html">
    <link rel="import" href="../paper-icon-button/paper-icon-button.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-icon-button icon="flag:ad"></paper-icon-button>
<paper-icon-button icon="flag:ag"></paper-icon-button>
<paper-icon-button icon="flag:ar"></paper-icon-button>
```
