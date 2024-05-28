# linux-xanmodv4-anbox-cjk

archlinux package

use the linux xanmodx64-v4 version for amd zen4

support anbox/waydroid

support cjk-tty

目前在配置中写死为 amd 体系结构，如果是 intel cpu 则改为\_microarchitecture=98

当前配置如下:

\_microarchitecture=99

use_numa=n

use_tracers=n

\_config=config_x86-64-v4

使用：makepkg -sficC
