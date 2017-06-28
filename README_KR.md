# things-theme

### 각각 다른 성격의 theme를 작성하여 필요할시 import해줌

Example:

```html
<link rel="import" id="theme" href="../../bower_components/things-theme/things-hassed-theme.html">
<style include="things-hassed-theme"></style>
```

Styling:

```html
<script type="text/javascript" src="things-xmes-theme-grid.js"></script>
<dom-module id="things-oi-theme">
  <template>
    <style>

    </style>
  </template>
</dom-module>
```

|Theme Name               |Theme HTML                                                                   |
|-------------------------|-----------------------------------------------------------------------------|
|things-hassed-theme      |`<link rel="import" href="../things-theme/things-hassed-theme.html">`        |
|things-label-theme       |`<link rel="import" href="../things-theme/things-label-theme.html">`         |
|things-oi-theme          |`<link rel="import" href="../things-theme/things-oi-theme.html">`            |
|things-point-theme       |`<link rel="import" href="../things-theme/things-point-theme.html">`         |
|things-xmes-theme        |`<link rel="import" href="../things-theme/things-xmes-theme.html">`          |
|things-sms-theme         |`<link rel="import" href="../things-theme/things-sms-theme.html">`           |

# things-xmes-theme

An element providing a starting point for your own reusable Polymer elements.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-xmes-theme/`, where `things-xmes-theme` is the name of the directory containing it.


## Example 1. Things XMES Theme
`<things-xmes-theme>` Things XMES Theme
