
# OpenJDK源码编译

- 源码版本 `OpenJDK9`
- 系统 `Ubuntu20.04 ` 
- boot JDK：`JDK 1.8.0_271 (build 1.8.0_271-b09)`

## 操作指南

1. configure

> `./configure --with-boot-jdk=/usr/lib/jvm/jdk1.8.0_271 --disable-warnings-as-errors`  

<div align ="center" >
    <img src="./images/configure_success.png" >
</div>  

2. 编译JDK  

> `make all`

<div align ="center" >
    <img src="./images/make_success.png" >
</div>

3. OpenJDK 9的编译输出  

    编译完成，build目录下会生成一个`linux-x86_64-normal-server-release`目录，所有的编译成果均位于其中。
    编译后的JDK在 `jdk源码根目录/build/linux-x86_64-normal-server-release/images`

<div align ="center" >
    <img src="./images/build_openjdk.png" >
</div>  



<br>

# Welcome to OpenJDK!

## 官方推荐编译配置  

<div>
    <img src="./images/OpenJDK9_base.png" >
</div>
<br>  

## 官方操作指南  

For information about building OpenJDK, including how to fully retrieve all
source code, please see either of these:

  * common/doc/building.html   (html version)
  * common/doc/building.md     (markdown version)

See http://openjdk.java.net/ for more information about OpenJDK.
