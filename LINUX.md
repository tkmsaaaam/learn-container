### How to Start Linux
- https://users.miraclelinux.com/technet/document/linux/training/1_1_1.html

### Linuxの起動プロセス
- ブートプロセス
  - BIOS(Basic Input Output System)
    - MBR(Master Boot Record)
  - ブートローダー
    - `/boot`の読み込み
  - カーネル
    - `boot/initrd`の読み込み(initial ramdisk)
    - `/root`の読み込み
  - initプログラム
    - `/etc/inittab`の読み込み
- GRUB(Grand Unified Bootloader)
  - `/boot/grub/grub.conf`を読み込み
  - OSを起動