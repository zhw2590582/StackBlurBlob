# stackBlurToUrl

The core code comes from here
[http://www.quasimondo.com/StackBlurForCanvas/StackBlurDemo.html](http://www.quasimondo.com/StackBlurForCanvas/StackBlurDemo.html)

## Install

Install with `npm`

```
$ npm install stackBlurToUrl
```

Or install with `yarn`

```
$ yarn add stackBlurToUrl
```

```js
import stackBlurToUrl from 'stackBlurToUrl';
```

Or umd builds are also available

```html
<script src="path/to/stackBlurToUrl.js"></script>
```

Will expose the global variable to `window.stackBlurToUrl`.

## Usage

```js
// Only need image address and blur radius
stackBlurToUrl('./banner.png', 100).then(url => {
    console.log(url);
});
```

## License

MIT © [Harvey Zack](https://www.zhw-island.com/)
