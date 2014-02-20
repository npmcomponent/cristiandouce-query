*This repository is a mirror of the [component](http://component.io) module [cristiandouce/query](http://github.com/cristiandouce/query). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/cristiandouce-query`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# query

  X-Browser DOM element query supported by [sizzle](https://github.com/cristiandouce/sizzle)

## Installation

  Install with [component(1)](http://component.io):

    $ component install cristiandouce/query

## API

```js
var o = require('query');

// Query single elements
var container = o('#container'); // 'div#container'

var firstItem = o('ul li'); // 'ul li'

// Query all matching elements
var fullItems = o.all('ul li'); // ['ul li', 'ul li', ...]
```

## License

  MIT
