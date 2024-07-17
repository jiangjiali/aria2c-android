# aria2c-android
[![Latest build](https://github.com/jiangjiali/aria2c-android/actions/workflows/build.yml/badge.svg?query=branch%3Amaster)](https://github.com/jiangjiali/aria2c-android/actions/workflows/build.yml/badge.svg?query=branch%3Amaster)

交叉编译[aria2](https://github.com/aria2/aria2)，Android运行库

## 构建

克隆带有子模块（`-reurse submoduls`）的存储库，安装Android NDK r26d，设置`Android_NDK_HOME`环境变量并运行 `/build_all.sh`。

这将编译`armavi-v7a`、`arm64-v8a`的aria2。二进制文件可以在“bin”文件夹中找到。
