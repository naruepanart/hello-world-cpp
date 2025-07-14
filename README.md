# hello-world-cpp

Production

```
g++ main.cpp -O3 -s -DNDEBUG -flto
```

Production-Safe

```
g++ main.cpp -O2 -s -DNDEBUG -flto
```

Aggressive-Embedded-Systems

```
g++ main.cpp -O3 -s -DNDEBUG -flto -ffunction-sections -fdata-sections -Wl,--gc-sections
```
