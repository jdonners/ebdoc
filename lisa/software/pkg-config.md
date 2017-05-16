## Introduction
pkg-config is a helper tool used when compiling applications and libraries. It helps you insert the correct compiler options on the command line so an application can use gcc -o test test.c `pkg-config --libs --cflags glib-2.0` for instance, rather than hard-coding values on where to find glib (or other libraries). 

pkg-config is available using the command:

```
module load pkg-config
```

* [More about pkg-config](http://www.freedesktop.org/wiki/Software/pkg-config/)
* [More about modules](Local:/systems/lisa/software/modules)

Available versions:

* 0.29.1-intel-2016b (new from 26-04-2017)