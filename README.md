# Freax

种种契机，想玩玩操作系统了。

发现一个宝藏网站：http://www.oldlinux.org/

顺便读读书吧，《Linux内核完全注释》

![](http://www.oldlinux.org/download/clk011.jpg)

该书的最新修订版 PDF 在 http://www.oldlinux.org/book.html 文末，自己找找吧～

## Linux 0.11 内核源码

http://www.oldlinux.org/Linux.old/kernel/0.1x/

按需下载压缩包就行，例如 linux-0.11.tar.gz

## Mac M1 下构建步骤

### 1. 安装 qemu

```shell
# install
brew install qemu
# check
brew info qemu
# uninstall
brew uninstall qemu
```

### 2. 安装 i386-elf-binutils i386-elf-gcc

```shell
# deprecated
# brew install i386-elf-binutils i386-elf-gcc
brew install x86_64-elf-gcc x86_64-elf-gdb x86_64-elf-binutils

# check
brew info x86_64-elf-gcc
brew info x86_64-elf-gdb
brew info x86_64-elf-binutils
```

可以看到，`i386-elf-gcc` 已经过时了，实际安装的是 `x86_64-elf-gcc`。
Warning: Use x86_64-elf-gcc instead of deprecated i386-elf-gcc
x86_64-elf-gcc: stable 12.1.0 (bottled)

可以看到，`i386-elf-binutils` 已经过时了，实际安装的是 `x86_64-elf-binutils`。
Warning: Use x86_64-elf-binutils instead of deprecated i386-elf-binutils
x86_64-elf-binutils: stable 2.38 (bottled)

### 3. 开搞


## 做点啥呢？

总得有一技之长吧，至少对某个技术了如指掌，什么技术呢？现在还不知道
