```
martin@yobbo:/usr/local/boost_1_51_0/lib$ find -P ./ -type f -name "*.so*" | xargs ldd | grep boost|sed -e "s/://g" -e "s/ => not found//g"
./libboost_context.so.1.51.0
./libboost_program_options.so.1.51.0
./libboost_signals.so.1.51.0
./libboost_regex.so.1.51.0
./libboost_math_tr1l.so.1.51.0
./libboost_graph.so.1.51.0
        libboost_regex.so.1.51.0
./libboost_python.so.1.51.0
./libboost_math_c99l.so.1.51.0
./libboost_system.so.1.51.0
./libboost_serialization.so.1.51.0
./libboost_random.so.1.51.0
./libboost_iostreams.so.1.51.0
./libboost_chrono.so.1.51.0
        libboost_system.so.1.51.0
./libboost_timer.so.1.51.0
        libboost_chrono.so.1.51.0
        libboost_system.so.1.51.0
./libboost_thread.so.1.51.0
        libboost_chrono.so.1.51.0
        libboost_system.so.1.51.0
./libboost_filesystem.so.1.51.0
        libboost_system.so.1.51.0
./libboost_date_time.so.1.51.0
./libboost_math_tr1f.so.1.51.0
./libboost_math_c99.so.1.51.0
./libboost_prg_exec_monitor.so.1.51.0
./libboost_unit_test_framework.so.1.51.0
./libboost_locale.so.1.51.0
        libboost_thread.so.1.51.0
        libboost_chrono.so.1.51.0
        libboost_system.so.1.51.0
./libboost_math_tr1.so.1.51.0
./libboost_wave.so.1.51.0
        libboost_date_time.so.1.51.0
        libboost_thread.so.1.51.0
        libboost_chrono.so.1.51.0
        libboost_filesystem.so.1.51.0
        libboost_system.so.1.51.0
./libboost_math_c99f.so.1.51.0
./libboost_wserialization.so.1.51.0
        libboost_serialization.so.1.51.0
```
---
![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/boost-dep/boost-dep-tree-00.dot.png "00 - first basic version")
---
![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/boost-dep/boost-dep-tree-01.dot.png "01")
---
![Alt text](https://raw.github.com/mbohun/mbohun_graph-experiments/master/boost-dep/boost-dep-tree-02.dot.png "02")
---
<img src="https://raw.githubusercontent.com/mbohun/mbohun_graph-experiments/master/boost-dep/boost-dep-tree-02.dot.svg"></img>
