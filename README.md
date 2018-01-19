## Python-learn

### Mac安装python3

如果你正在使用Mac系统是OS X 10.8~10.10及以上，那么系统自带的Python版本是2.7。要安装最新的Python 3.6，有两个方法：

* 方法一：从Python官网下载Python 3.6的安装程序，双击运行并安装；

* 方法二：如果安装了Homebrew，直接通过命令brew install python3安装即可。

1. 常见问题

* `brew install python3`安装完成后报错，无法link

Linking /usr/local/Cellar/python3/... Error: Permission denied @ dir_s_mkdir - /usr/local/Frameworks

解决方案：

```bash
>sudo mkdir /usr/local/Frameworks
>sudo chown $(whoami):admin /usr/local/Frameworks
>brew link python3
```


---
### 与Javascript的比较

1. 数据类型和变量
