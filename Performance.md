# Performance

## Minify, Compress, Cache!

Minifying, compressing, and caching files can all make a difference in performance. Minifying and compressing reduce the number of bytes fetched, and caching reduces the frequency of fetching.

### Minify

Minification is the process of removing all unnecessary characters from source code without changing the functionality of the code. Stripping the parts of the code that make it readable can make it more performant.

Use Google to find a minifying service you like.

### Compress

Compression takes minification a step further by condensing your code to as few characters as possible without changing the functionality of the code. Compressed code must be uncompressed first before execution, unlike minified code which is still valid.

Use Google to find a compression service you like.

### Cache

Caching is a tool the browser uses to access previously fetched files without having to go and retrieve them again. The browser does this by itself, but there are a few ways you can work with the browser to optimize caching.

You can use the Expires header to set when the webpage expires:
* Expires: Wed, 21 Oct 2015, 19:28:00

You can use the Cache Control superheader to control if and for how long a page is cached:
* Cache-Control: max-age = 86400 (seconds)
* Cache-Control: no-store
* Cache-Control: no-cache
* Cache-Control: public
* Cache-Control: private