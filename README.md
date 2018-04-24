# icon-button

A Polymer Element showing a stylized icon button.

### Example
```js
var clickListener = {
  onClick: function() {
    // on-click behavior
  }
};
```

```html
<icon-button
  click-listener="[[clickListener]]"
  icon="icons:polymer"
  style-class="style-class"
  title-tooltip="Text">
</icon-button>
```

### Styling

`<icon-button>` provides the following custom properties and mixins for styling:

Custom property                | Description                                             | Default
-------------------------------|---------------------------------------------------------|--------
`--icon-button-color`          | The color for the icon button.                          | --paper-grey-600
`--icon-button-mixin`          | The custom style mixin for the icon button.             | none
`--icon-button-active-color`   | The color for the icon button if active.                | --paper-grey-900
`--icon-button-active-mixin`   | The custom style mixin for the icon button if active.   | none
`--icon-button-disabled-color` | The color for the icon button if disabled.              | --paper-grey-300
`--icon-button-disabled-mixin` | The custom style mixin for the icon button if disabled. | none
`--icon-button-hovering-mixin` | The color for the icon button if hovering.              | --paper-grey-900
`--icon-button-hovering-mixin` | The custom style mixin for the icon button if hovering. | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

