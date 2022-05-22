# 可运行的镜像文件

使用 `./run.sh` 即可运行

## linux-0.00

> http://oldlinux.org/Linux.old/bochs/linux-0.00-050613.zip

只会打印AB，测试玩玩

## linux-0.11

> http://oldlinux.org/Linux.old/bochs/linux-0.11-devel-040923.zip

这里的 0.11 均使用的是 HD 后缀的，没有使用 FD。

- HD HardDisk 硬盘
- FD FloppyDisk 软盘

## linux-0.12

> http://oldlinux.org/Linux.old/bochs/linux-0.12-080324.zip

`rootimage-0.12-hd` 这个文件太大（近240MB），github提交报错如下，如有需要，从上边的链接下载吧～
`diskb.img` 不是必须的，其中包含了一些工具程序。在 Linux 0.12 中可以使用 mcopy 等命令来访问这两个文件。

```
warning: File images/linux-0.11/hdc-0.11.img is 59.55 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
remote: error: File images/linux-0.12/rootimage-0.12-hd is 239.70 MB; this exceeds GitHub's file size limit of 100.00 MB

可见，超过50MB会警告，超过100MB会报错。
```
