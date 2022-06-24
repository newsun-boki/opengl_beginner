# How to run

一个opengl的配置，使用glfw和glad,不知道为啥只有这样才可以运行起来。

## 环境
+ Windows10
+ VScode

```bash
g++ test.cpp glad.c -o test lib/libglfw3dll.a lib/libopengl32.a
```