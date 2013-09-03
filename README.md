# Bits.sass utilities: responsive display

Responsive superset of space utilities.

See [Bits.sass utils-display](https://github.com/bits-sass/utils-display) for more about
original utilities.

Read more about [Bits.sass toolkit](https://github.com/bits-sass/bits.sass).

## Installation

* __Bower:__ `bower install --save bits-sass-responsive-utils-display`
* __Download:__ [zip](https://github.com/bits-sass/responsive-utils-display/zipball/master), [tar.gz](https://github.com/bits-sass/responsive-utils-display/tarball/master)
* __Git:__ `git clone https://github.com/bits-sass/responsive-utils-display.git`

## Available SASS variables

* `bits-utils-ns` - utilities namespace, defaults to 'bits-'

## Available utility classes

* `v1-u-none` - display none by default (no breakpoint)
* `v[n]-u-none` - display none on `n` breakpoint
* `v[n]-u-inline` - inline on `n` breakpoint
* `v[n]-u-inlineBlock` - inline-block on `n` breakpoint
* `v[n]-u-block` - block on `n` breakpoint
* `v[n]-u-table` - table on `n` breakpoint
* `v[n]-u-tableCell` - table-cell on `n` breakpoint

## Usage

Hide a block by default, show it at `v4` breakpoint. Use in situations that you
would say: "Show this only on wider screens".

```html
<div class="v1-u-none v4-u-block">
 …
</div>
```

Hide a block on `v4` breakpoint. Use in situations that you
would say: "Show this on narrow screen only".

```html
<div class="v4-u-none">
 …
</div>
```

## Requirements

* Sass 3.2+

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 9+ (IE 8 requires a build step)