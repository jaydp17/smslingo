# smslingo
A simple node.js module that detects and converts SMS language abbreviations to regular text.

```javascript
var SmsLingo = require('smslingo');
var sms = new SmsLingo();

sms.isAbbr('der'); // true
sms.text('der'); // there
sms.statement('b der @ 10am'); // be there at 10am
```

Internally smslingo uses a mapping that maps abbreviations to their actual text.

Installation
----
```sh
npm install smslingo
```

License
---
MIT. See "LICENSE.txt".
