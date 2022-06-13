# CMakeTutorials



CMake是一个构建系统，可以用于构建跨平台的C和C++项目。其它的构建系统有makefile、MSBuild以及qmake。



## 引入

最基础的项目是将**源代码**构建成**可执行文件**。对于一个简单的项目，只需要一个3行的`CMakeLists.txt`文件即可。

```cmake
# cmake最低版本
cmake_minimum_required(VERSION 3.10)

# 设置项目名
project(Tutorial)

# 添加可执行目标
add_executable(Tutorial tutorial.cpp)
```

其中，`tutorial.cpp`是一个c++的源代码文件。

代码见Step1（单文件 CMakeLists.txt）。

