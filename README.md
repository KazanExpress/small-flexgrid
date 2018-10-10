# small-flexgrid.styl

> A small flexgrid written in Stylus

## Usage

`npm install --save small-flexgrid`

```scss
@import 'small-flexgrid';
/* or, for css: */
@import 'small-flexgrid/.css';
/* or, for prefixed css */
@import 'small-flexgrid/prefixed.css';
```

```js
import 'small-flexgrid';
// or, for css:
import 'small-flexgrid/.css';
// or, for prefixed css
import 'small-flexgrid/prefixed.css';
```

**OR**

```html
<link rel="stylesheet" href="https://unpkg.com/small-flexgrid/min.css">
<!-- OR -->
<link rel="stylesheet" href="https://unpkg.com/small-flexgrid/prefixed.min.css">
```

You can also import mixins separately:
```scss
@import 'small-flexgrid/src/mixins';
```

**THEN** (if using stylus only)

in your styles

```scss
cols-amount = 12 // basically, any amount you want
sizes = {        // basically, any breakpoints you want
  all: 0rem
  xs: 20rem
  sm: 33.75rem
  md: 48rem
  lg: 63.75rem
  xl: 76.25rem
}
col-suffix = '-my-cool'

cols(cols-amount, sizes, col-suffix) // generate all columns

helpers(cols-amount, sizes, col-suffix)  // generate helpers

cols-with-helpers(cols-amount, sizes, col-suffix) // generate all columns AND helpers
```

