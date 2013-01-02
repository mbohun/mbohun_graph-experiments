# emtoodee M (em) inimalist 2 (too) D (dee) java engine
![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/emtoodee-design/screenshots/martin-bohun_game-engine-2012-00.png "java applet version")

![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/emtoodee-design/screenshots/mb-e2d-00_shadowsoft.png "screenshot")![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/emtoodee-design/screenshots/mb-e2d-01_shadowsoft.png "screenshot")

![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/emtoodee-design/animation_walker_demo.gif "walking")[demo](http://users.on.net/~mbohun)
---
## architecture & design
![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/emtoodee-design/engine-architecture.png "first version created in dia")

## features
- java version (java applet, standalone java app, android)
- native version (C, OpenGL ES, NDK on android)
- modular (originally written as a benchmark to compare/eval diff alternative implementations)
- realtime diagnostic (over UDP, TCP)
- full replay/persistance (save/restore state)
- screenshots, "gameplay" video recording (requires ffmpeg)
- support for 3rd party [map editor](http://www.mapeditor.org)
- written to be extended/customized

---
_alternative diagram-s created/generated with graphviz dot_
![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/emtoodee-design/architecture-01.dot.png "first version created/generated with graphviz DOT")

![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/emtoodee-design/architecture-01-sink.dot.png "fixed/alternative layout")
