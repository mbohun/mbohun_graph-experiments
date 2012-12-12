# objective
This was an experiment/test of how to get a SVG/SVGZ image displayed inline on github.

# conclusion/result
(as of December 2012) the only way seem to be to use the `<img>` tag with the `src` attribute set to a SVG/SVGZ file-s hosted NOT at github:
```
<img src="http://users.on.net/~mbohun/src/architecture-01-sink.dot.svg"></img>
```
<img src="http://users.on.net/~mbohun/src/architecture-01-sink.dot.svg"></img>

```
<img src="http://users.on.net/~mbohun/src/boost-dep-tree.dot.svgz"></img>
```
<img src="http://users.on.net/~mbohun/src/boost-dep-tree.dot.svgz"></img>

---
NOTE:
If firefox and/or google-chrome (opera works fine) fails to display .svgz file-s, add this to your `.htaccess` file on the server:
```
AddType image/svg+xml svg svgz
AddEncoding gzip svgz
```
