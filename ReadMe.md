# Valgrind Exercise

ENPM808X - Week 6
Tanuj Thakkar (tanuj@umd.edu)
---

## Compile and Build

```
mkdir build
cd build
cmake ..
make
```

## Valgrind

```
valgrind --leak-check=full ./app/shell-app
```

## KCachegrind Memory Profiler

```
valgrind --tool=callgrind ./app/shell-app
```