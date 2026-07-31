# linux-xanmod-anbox-cjk

archlinux package

基于 xanmod 7.1.5，使用其 7.1 分支的基础配置（config）为 amd zen4 编译

support anbox/waydroid

support cjk-tty

目前在配置中写死为 amd zen4 体系结构（\_microarchitecture=14），如果是 intel cpu 则改为 \_microarchitecture=98

当前配置如下:

\_microarchitecture=14  (amd zen4)

use_numa=n

use_tracers=n

\_config=config

使用：makepkg -sficC

遇到证书问题：

gpg --recv-keys 38DBBDC86092693E
