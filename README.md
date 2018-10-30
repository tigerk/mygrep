# mygrep

使用Rust Lang实现了grep功能，支持设置大小写敏感设置。

> 在开始前请先安装Rust，请参考https://kaisery.github.io/trpl-zh-cn/ch01-01-installation.html


打开命令行
```
// 在peom.txt中查找to
$ cargo run to peom.txt

// 设置为大小写不敏感
$ CASE_INSENSITIVE=1 cargo run to poem.txt
```
