le.js
=====

Client-side JavaScript library for [Logentries](http://www.logentries.com).

[![Build Status](https://travis-ci.org/logentries/le_js.png?branch=master)](https://travis-ci.org/logentries/le_js)

Want to get under the hood? Check out the [wiki](https://github.com/logentries/le_js/wiki)

Features
--------

* Small: ~2k (minified)
* Cross-browser compatible
* No external dependencies
* Simple API

Usage
-----

* Get the latest build [here](https://github.com/logentries/le_js/tree/master/product) or download a [source release](https://github.com/logentries/le_js/releases).

* Include the library in your page:

```html
<html lang="en">
  <head>
    <title>Your page</title>
    <script src="/js/le-VERSION.min.js"></script>
    <script>
      // Create a log stream...
      LE.init('YOUR-TOKEN');
      // ...and log some events!
      LE.log("Hello, logger!");
    </script>
  </head>
  ...

```

Check out the [API](https://github.com/logentries/le_js/wiki/API) for more details.

Need a token? Get a [free account](https://logentries.com/quick-start/) if you don't already have one.

