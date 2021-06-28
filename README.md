# allegro5_poc 

-------------------------------------------------
Verification steps：
1.Get the source code of allegro5
2.Compile the allegro5

```bash
$ mkdir build && cd build
$ cmake ../ -DCMAKE_C_COMPILER=clang -DCMAKE_CXX_COMPILER=clang++
$ make -j 32
$ cd examples
$ ./ex_bitmap poc
```

link add:https://github.com/liballeg/allegro5/issues/1251

commit:
https://github.com/liballeg/allegro5/pull/1253/commits/2c712d4c642ec59e3093299e271450146a9643a9
https://github.com/liballeg/allegro5/pull/1253/commits/4cd34dc8e4e746c190df240d0758333e929c1cf1
https://github.com/liballeg/allegro5/pull/1253/commits/c53381f3410a71a34e28f5e29b76f1e56f8ce708
https://github.com/liballeg/allegro5/pull/1253/commits/0d5f9e56e2cfefc57b30ef729615cb74287ab8d0
