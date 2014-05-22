## objective
This was an experiment/test of how to get SVG/SVGZ images displayed inline on github.

## conclusion/result
(as of December 2012) the only way seems to be to use the `<img>` tag with the `src` attribute set to a SVG/SVGZ file-s hosted NOT at github, i.e. some external file server:
```
<img src="http://users.on.net/~mbohun/src/architecture-01-sink.dot.svg"></img>
```
<img src="http://users.on.net/~mbohun/src/architecture-01-sink.dot.svg"></img>

or using amazon's s3:
```
<img src="https://s3.amazonaws.com/mbohun-public/architecture-01-sink.dot.svg"></img>
```
<img src="https://s3.amazonaws.com/mbohun-public/architecture-01-sink.dot.svg"></img>

```
<img src="http://users.on.net/~mbohun/src/boost-dep-tree.dot.svgz"></img>
```
<img src="http://users.on.net/~mbohun/src/boost-dep-tree.dot.svgz"></img>

---
### NOTE:
If firefox and/or google-chrome (opera works fine) fails to display .svgz file-s, add this to your `.htaccess` file on the server where you host your .svg/.svgz files:
```
AddType image/svg+xml svg svgz
AddEncoding gzip svgz
```
