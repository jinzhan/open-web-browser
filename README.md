# launchbrowser (url: string): boolean

Attempts to open the browser with a given URL.
On Mac OS X, attempts to reuse an existing Chrome tab via AppleScript.
Otherwise, falls back to opn behavior.


## Installation

```
npm install launchbrowser
```

## Usage

```
var path = require('path');
var openBrowser = require('launchbrowser');

if (openBrowser('http://localhost:3000')) {
  console.log('The browser tab has been opened!');
}
```


## License

MIT