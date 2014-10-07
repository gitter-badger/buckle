Buckle
======
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/tomas/buckle?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Pure JS ZIP extractor, that preserves file attributes. Based on a modified version of DecompressZip.

``` js

var buckle = require('buckle');

buckle.open('/path/to/package.zip', '/destination/path', function(err, result) {
  console.log(err || result);
})
```

That's pretty much it. You can omit the destination path argument, which will unzip the files to the package's current path.

Credits
-------

Written by Tomás Pollak.

Copyright
---------

(c) 2014 Fork Ltd. MIT licensed.