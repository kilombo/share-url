# \<share-url\>
[![license](https://img.shields.io/github/license/cluttered-components/online-status-icon.svg)](https://raw.githubusercontent.com/cluttered-components/online-status-icon/master/LICENSE)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/owner/share-url)

Element to share the current url

## DEMO
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="share-url.html">
    <share-url selected-networks='["Linkedin", "Facebook", "Twitter", "Google Plus", "Pinterest"]' share-text="SHARE"></share-url>
  </template>
</custom-element-demo>
```
-->

### Styling

Custom property | Description | Default
----------------|-------------|----------
`--share-url-border-color` | The color of the border for all icons | `#000000`


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
