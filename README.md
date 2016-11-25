# getbasis-page-effect
This is a css module for the Basis.

## Basis
* Repository: https://github.com/getbasis/basis/
* Documents : http://getbasis.github.io/

## Get Started

### Install
```
$ npm install getbasis
$ npm install getbasis-page-effect
```

### Stylus
```
@import 'node_modules/getbasis/src/stylus/basis';
@import 'node_modules/getbasis-page-effect/src/stylus/core/mixin/page-effect';
@import 'node_modules/getbasis-page-effect/src/stylus/core/placeholder/page-effect';
@import 'node_modules/getbasis-page-effect/src/stylus/object/component/page-effect';
```

### Javascript
```
import $ from 'jquery';
import BasisPageEffect from 'node_modules/getbasis-page-effect/src/js/page-effect.js';
new BasisPageEffect();
```

### HTML
```
<div class="c-page-effect" data-c="page-effect" data-page-effect="fade">
  <div class="c-page-effect__item">
    Loading...
  </div>
</div>
```

## Browser support
Modern Browser and IE10+

## License
MIT License
