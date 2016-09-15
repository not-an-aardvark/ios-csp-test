This is a demo of a Content-Security-Policy bug in iOS 10 Safari (as of September 15th, 2016).

The bug is that if a site has `connect-src: *` in its Content Security Policy, requests with different protocols (e.g. `wss:`) are incorrectly blocked.

Links:

* [Bug demo](https://not-an-aardvark.github.io/ios-csp-test/)
* [Content-Security-Policy spec](https://www.w3.org/TR/CSP2/#match-source-expression)
