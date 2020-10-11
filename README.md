# SuperPI

the source code of performing single thread CPU benchmark

-----

## build on linux
**use gcc :**

```gcc -O -funroll-loops -fomit-frame-pointer pi_fftcs.c fftsg_h.c -lm -o pi_css5```

**use makefile :**

```make all```

**use cmake :**

```mkdir build && cd build && cmake ..```
you can either open it in vscode and build with cmake plugin

-----
## run on linux

```./pi_css5 $((1<<20))```

*the parameter is the number of decimal digits you want to calculate in the program it will be round to the power of two*
