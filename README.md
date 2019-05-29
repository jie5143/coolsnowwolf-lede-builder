The builder for https://github.com/coolsnowwolf/lede

为https://github.com/coolsnowwolf/lede 项目制作的构建编译工具

```
docker run -it -v /home/lede_output:/lede/bin jie5143/lede
```

```
make menuconfig

...

make -j1 V=s
```
