<!--

@license Apache-2.0

Copyright (c) 2021 The Stdlib Authors.

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

# zeros

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Create a zero-filled "generic" array.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->



<section class="usage">

## Usage

To use in Observable,

```javascript
zeros = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/array-base-zeros@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var zeros = require( 'path/to/vendor/umd/array-base-zeros/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/array-base-zeros@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
(function () {
    window.zeros;
})();
})();
</script>
```

#### zeros( len )

Returns a zero-filled "generic" array.

```javascript
var out = zeros( 3 );
// returns [ 0.0, 0.0, 0.0 ]
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
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/blas-ext-base-gfill@umd/browser.js"></script>
<script type="text/javascript">
(function () {
(function () {.ndarray;
var zeros = require( '@stdlib/array-base-zeros' );

// Create a zero-filled array:
var arr = zeros( 10 );

// Fill element pairs with the same value...
gfill( 2, 1.0, arr, 1, 0 );
gfill( 2, 2.0, arr, 1, 2 );
gfill( 2, 3.0, arr, 1, 4 );
gfill( 2, 4.0, arr, 1, 6 );
gfill( 2, 5.0, arr, 1, 8 );

console.log( arr );
// => [ 1.0, 1.0, 2.0, 2.0, 3.0, 3.0, 4.0, 4.0, 5.0, 5.0 ]

})();
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

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/array-base-zeros.svg
[npm-url]: https://npmjs.org/package/@stdlib/array-base-zeros

[test-image]: https://github.com/stdlib-js/array-base-zeros/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/array-base-zeros/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/array-base-zeros/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/array-base-zeros?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/array-base-zeros.svg
[dependencies-url]: https://david-dm.org/stdlib-js/array-base-zeros/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/array-base-zeros/tree/deno
[umd-url]: https://github.com/stdlib-js/array-base-zeros/tree/umd
[esm-url]: https://github.com/stdlib-js/array-base-zeros/tree/esm
[branches-url]: https://github.com/stdlib-js/array-base-zeros/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/array-base-zeros/main/LICENSE

</section>

<!-- /.links -->
