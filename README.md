ember-content-loader
==============================================================================

SVG-Powered component to easily create skeleton screens / placeholder loadings (like Facebook's cards loading).


Compatibility
------------------------------------------------------------------------------

* Ember.js v2.18 or above
* Ember CLI v2.13 or above
* Node.js v8 or above


Installation
------------------------------------------------------------------------------

```
ember install ember-content-loader
```


Usage
------------------------------------------------------------------------------

![Facebook skeleton](https://user-images.githubusercontent.com/4838076/34308760-ec55df82-e735-11e7-843b-2e311fa7b7d0.gif)

Simply add the `<ContentLoader>` component in your code with the shapes that you want.

```hbs
<ContentLoader>
  {{!-- Only SVG shapes --}}
  <rect x="70" y="15" rx="4" ry="4" width="117" height="6.4" />
  <rect x="70" y="35" rx="3" ry="3" width="85" height="6.4" />
  <rect x="0" y="80" rx="3" ry="3" width="350" height="6.4" />
  <rect x="0" y="100" rx="3" ry="3" width="380" height="6.4" />
  <rect x="0" y="120" rx="3" ry="3" width="201" height="6.4" />
  <circle cx="30" cy="30" r="30" />
</ContentLoader>
```

You can use the [online editor](http://danilowoz.com/create-content-loader/) to create complex shapes.

> **Note:** This editor is made for React, so you need to translate the produced code.


Options
------------------------------------------------------------------------------

You can find all `<ContentLoader>` available options [here](https://concordnow.github.io/ember-content-loader/docs/api/components/content-loader)


Contributing
------------------------------------------------------------------------------

See the [Contributing](CONTRIBUTING.md) guide for details.


License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
