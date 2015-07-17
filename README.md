# Infobox

This is git port of the infobox library from [google-maps-utility-library-v3](http://google-maps-utility-library-v3.googlecode.com/svn/trunk/infobox/).

### Changes

* The infobox will center itself vertically over the marker, although the pixelOffset option can still be used to adjust the position.
* Disabled the auto panning function, this means the disableAutoPan option has no effect.
* Disabled the alignBottom option, internally this is always set to false.

### Build

To build a minified version of the library using uglify:
(requires node.js)

```bash
$ npm install
$ npm run build
```

### License

[Apache License, Version 2.0](http://opensource.org/licenses/Apache-2.0)
