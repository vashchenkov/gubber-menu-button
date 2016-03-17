
<!---

This README is automatically generated from the comments in these files:
gubber-menu-button-animations.html  gubber-menu-button.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/PolymerElements/gubber-menu-button.svg?branch=master)](https://travis-ci.org/PolymerElements/gubber-menu-button)

_[Demo and API docs](https://elements.polymer-project.org/elements/gubber-menu-button)_


##&lt;gubber-menu-button&gt;

Material design: [Dropdown buttons](https://www.google.com/design/spec/components/buttons.html#buttons-dropdown-buttons)

`gubber-menu-button` allows one to compose a designated "trigger" element with
another element that represents "content", to create a dropdown menu that
displays the "content" when the "trigger" is clicked.

The child element with the class `dropdown-trigger` will be used as the
"trigger" element. The child element with the class `dropdown-content` will be
used as the "content" element.

The `gubber-menu-button` is sensitive to its content's `iron-select` events. If
the "content" element triggers an `iron-select` event, the `gubber-menu-button`
will close automatically.

Example:

```html
<gubber-menu-button>
  <paper-icon-button icon="menu" class="dropdown-trigger"></paper-icon-button>
  <paper-menu class="dropdown-content">
    <paper-item>Share</paper-item>
    <paper-item>Settings</paper-item>
    <paper-item>Help</paper-item>
  </paper-menu>
</gubber-menu-button>
```

### Styling

The following custom properties and mixins are also available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--gubber-menu-button-dropdown-background` | Background color of the gubber-menu-button dropdown | `--primary-background-color` |
| `--gubber-menu-button` | Mixin applied to the gubber-menu-button | `{}` |
| `--gubber-menu-button-disabled` | Mixin applied to the gubber-menu-button when disabled | `{}` |
| `--gubber-menu-button-dropdown` | Mixin applied to the gubber-menu-button dropdown | `{}` |
| `--gubber-menu-button-content` | Mixin applied to the gubber-menu-button content | `{}` |



<!-- No docs for <paper-menu-grow-height-animation> found. -->

<!-- No docs for <paper-menu-grow-width-animation> found. -->

<!-- No docs for <paper-menu-shrink-height-animation> found. -->

<!-- No docs for <paper-menu-shrink-width-animation> found. -->
