这里也没啥，刷机包是不可能传上来的，大不了就是些命令？！

这里写的都是我手上那台小米5s(xiaomi 5s-capricorn)的资源

## 前置资源
[MI5S原生ROM 整合及教程贴](https://www.jianshu.com/p/a1c97771107c?_wv=1031)

[MI5S官方ROM](https://www.miui.com/download-319.html)

[MIUI官方解锁](http://www.miui.com/unlock/index.html)

## adb命令行

查看adb连接状态
```
adb devices
```
重启至引导模式
```
adb reboot bootloader
```
重启至恢复模式
```
adb reboot recovery
```

## fastboot命令行

刷写recovery
```
fastboot flash recovery [文件路径/文件名.img]
```
重启
```
flash reboot
```
