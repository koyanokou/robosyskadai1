# robosyskadai1
# ロボットシステム学課題１
## 概要
LEDのオン，オフを切り替える．
## デバイスドライバの作成
```
$ git clone https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts.git
$ cd raspberry_pi_kernel_build_scripts
$ sudo ./karnel_build_and_install_for_pi2_pi3.bash
$ sudo reboot
```
## 動画のURL
https://youtu.be/LiomWKTOCwo

## 使用方法
```
$ https://github.com/koyanokou/robosyskadai1.git
$ cd robsys1
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
```
LEDを点灯に切り替え．
`$ echo 1 > /dev/myled0`
LEDを消灯に切り替え．
`$ echo 1 > /dev/myled0`

