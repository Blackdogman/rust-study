# 这是一个自用学习rust语言的项目,记录学习历程
## 学习资料来源
1. [Hello,World!-Rust程序设计语言](https://kaisery.github.io/trpl-zh-cn/ch01-02-hello-world.html)
## 如何编译与执行rust文件(*.rs)
1. 编译二进制
```shell
$ rustc hello_world.rs
```
2. 执行遍以后的二进制
```shell
$ ./hello_world # 类linux环境
$ ./hello_world.exe # windows环境
```
## cargo引用依赖
1. 编辑cargo.toml在[dependencies]标签下添加引用包的名称与版本
```toml
[dependencies]

rand = "0.8.3"
```

### 疑问记录
1. catgo.toml = package.xml?
