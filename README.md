<!--

@license Apache-2.0

Copyright (c) 2023 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# isRealDataType

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test if an input value is a supported ndarray real-valued data type.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->



<section class="usage">

## Usage

To use in Observable,

```javascript
isRealDataType = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/ndarray-base-assert-is-real-data-type@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var isRealDataType = require( 'path/to/vendor/umd/ndarray-base-assert-is-real-data-type/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/ndarray-base-assert-is-real-data-type@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.isRealDataType;
})();
</script>
```

#### isRealDataType( value )

Tests if an input `value` is a supported ndarray real-valued data type.

```javascript
var bool = isRealDataType( 'float32' );
// returns true

bool = isRealDataType( 'uint32' );
// returns true
```

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/ndarray-base-assert-is-real-data-type@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var bool = isRealDataType( 'binary' );
// returns false

bool = isRealDataType( 'float32' );
// returns true

bool = isRealDataType( 'float64' );
// returns true

bool = isRealDataType( 'complex128' );
// returns false

bool = isRealDataType( 'generic' );
// returns false

bool = isRealDataType( 'int16' );
// returns true

bool = isRealDataType( 'int32' );
// returns true

bool = isRealDataType( 'int8' );
// returns true

bool = isRealDataType( 'uint16' );
// returns true

bool = isRealDataType( 'uint32' );
// returns true

bool = isRealDataType( 'uint8' );
// returns true

bool = isRealDataType( 'uint8c' );
// returns true

bool = isRealDataType( '' );
// returns false

bool = isRealDataType( 'foo' );
// returns false

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/ndarray-base-assert-is-real-data-type.svg
[npm-url]: https://npmjs.org/package/@stdlib/ndarray-base-assert-is-real-data-type

[test-image]: https://github.com/stdlib-js/ndarray-base-assert-is-real-data-type/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/ndarray-base-assert-is-real-data-type/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/ndarray-base-assert-is-real-data-type/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/ndarray-base-assert-is-real-data-type?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/ndarray-base-assert-is-real-data-type.svg
[dependencies-url]: https://david-dm.org/stdlib-js/ndarray-base-assert-is-real-data-type/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/ndarray-base-assert-is-real-data-type/tree/deno
[umd-url]: https://github.com/stdlib-js/ndarray-base-assert-is-real-data-type/tree/umd
[esm-url]: https://github.com/stdlib-js/ndarray-base-assert-is-real-data-type/tree/esm
[branches-url]: https://github.com/stdlib-js/ndarray-base-assert-is-real-data-type/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/ndarray-base-assert-is-real-data-type/main/LICENSE

</section>

<!-- /.links -->
