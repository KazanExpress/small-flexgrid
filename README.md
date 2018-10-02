# small-flexgrid.less

> A small flexgrid written in Less

## Usage

`npm install --save small-flexgrid`

```less
@import 'small-flexgrid';
/* or, for css: */
@import 'small-flexgrid/.css';
/* or, for prefixed css */
@import 'small-flexgrid/prefixed.css';
```

```js
import 'small-flexgrid'
// or, for css:
import 'small-flexgrid/.css'
// or, for prefixed css
import 'small-flexgrid/prefixed.css'
```

**OR**

```html
<link rel="stylesheet" href="https://unpkg.com/small-flexgrid/min.css">
<!-- OR -->
<link rel="stylesheet" href="https://unpkg.com/small-flexgrid/prefixed.min.css">
```

Usecases and API are almost identical to [flexboxgrid by kristoferjoseph](http://flexboxgrid.com)

You can also import media variables separately:
```less
@import 'small-flexgrid/vars.less';
```