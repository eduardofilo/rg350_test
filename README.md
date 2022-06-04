# RG350 Test
Application to test RG350: joysticks, pad, buttons, mouse, sound,sdcards.

# Author
Rafa Vico
http://github.com/rafavico

# License
GPL v.2

# Screenshots
<img src="https://github.com/RafaVico/rg350_test/blob/master/recursos/rgtest_04.png" alt="image">
<img src="https://github.com/RafaVico/rg350_test/blob/master/recursos/rg350test_v13c.png" alt="image">

# Compiling

## libShake

This lib have to be installed in the toolchain:

```
git clone https://github.com/zear/libShake.git
cd libShake
PLATFORM=gcw0 BACKEND=LINUX make install
```

## RG350 test

```
cd rg350_test
make clean
make
./make_opk.sh
```
