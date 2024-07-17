# aria2c-android
[![Build](https://github.com/jiangjiali/aria2c-android/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/jiangjiali/aria2c-android/actions/workflows/build.yml)

交叉编译[aria2](https://github.com/aria2/aria2)，Android运行库

## 构建

克隆带有子模块（`-reurse submoduls`）的存储库，安装Android NDK r26d，设置`Android_NDK_HOME`环境变量并运行 `/build_all.sh`。

这将编译`armavi-v7a`、`arm64-v8a`的aria2。二进制文件可以在“bin”文件夹中找到。

## 依赖版本
* aria2 v1.37.0
* c-ares v1.29.0
* libexpat v2.5.0
* libssh2 v1.11.0
* openssl v3.0.0
* zlib v1.3.1