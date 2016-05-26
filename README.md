Node-wintab
===
node.js wintab binding for getting wacom tablet pressure data.

Windows only.

updated with latest v8 API per update guidelines [here](https://strongloop.com/strongblog/node-js-v0-12-c-apis-breaking/)

Install
---
### prerequisite

 * python 2.x
 * MSVC++
 * node-gyp

### run
```
npm install node-wintab
```

Usage
---

```js
var wintab = require('node-wintab');
setInterval(function () {
    console.log(wintab.allData());
}, 1);
```

Test
---
`node index`


License
---

The MIT License (MIT)

Copyright (c) 2014, JongChan Choi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
