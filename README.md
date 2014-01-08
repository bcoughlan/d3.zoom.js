This is a standalone d3.js [zoom behavior](https://github.com/mbostock/d3/wiki/Zoom-Behavior),
for those who need pan and zoom behavior without the overhead of d3.js.

~45kb uncompressed, ~28kb minified, ~8kb gzipped.


Built from https://github.com/mbostock/d3/blob/master/src/behavior/zoom.js with
[SMASH](https://github.com/mbostock/smash) and [UglifyJS](https://github.com/mishoo/UglifyJS):

```
echo "d3 = {};" > d3.zoom.js; 
smash d3/src/behavior/zoom.js >> d3.zoom.js
uglifyjs d3.zoom.js > d3.zoom.min.js
```
