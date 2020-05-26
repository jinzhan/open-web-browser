# open-browser

> This package is extracted from
https://github.com/facebook/create-react-app/blob/master/packages/react-dev-utils/openBrowser.js

Attempts to open the browser with a given URL.
On Mac OS X, attempts to reuse an existing Chrome tab via AppleScript.
Otherwise, falls back to opn behavior.


## Installation

```
npm install @jinzhan/open-browser
```

## Usage (url: string): boolean

```
var path = require('path');
var openBrowser = require('@jinzhan/open-browser');

if (openBrowser('http://localhost:3000')) {
  console.log('The browser tab has been opened!');
}
```


## License

MIT