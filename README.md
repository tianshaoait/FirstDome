# FirstDome
# [![](https://jitpack.io/v/helen-x/JitpackReleaseDemo.svg)](https://jitpack.io/#helen-x/JitpackReleaseDemo)


# 1.生成一个依赖module
# 2.打开 Project 的 root build.gradle，在 dependencies 节点添加一个 classpath：
# classpath 'com.github.dcendents:android-maven-gradle-plugin:1.5'
# 3.打开 library 的 build.gradle，在文件起始添加如下两行 
# apply plugin: 'com.github.dcendents.android-maven' 
# group='com.github.xxx'(自己账户名)
# 4.push 到 GitHub 上
# 5.到JitPack.io 上面，Look up->Get it获取项目地址(到此github项目基本发布完)
# 6.要引用首先打开 Project root 的 build.gradle，在 repositories 节点添加上 maven { url "https://jitpack.io" }
# 7.在项目build.gradle的 dependencies 节点添加上 compile 'com.github.xxx:xxx:1.0'地址引用

# http://www.jianshu.com/p/e443456bb506
# 参考
