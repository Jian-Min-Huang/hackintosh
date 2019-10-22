# Spec
| Component | Brand | Model |
|:----------|:------|:------|
| CPU | Intel | i7-8700 |
| MB | ASUS | ROG STRIX H370-F GAMING |
| VGA | MSI | RX570 ARMOR 8G OC |
| SSD | Samsung | 970 PRO 512GB |
| SSD | CORSAIR | Force Series™ MP510 480GB M.2 SSD |
| RAM | CORSAIR | Vengeance RGB PRO D4-3000M C15 16G * 4 |
| PSU | CORSAIR | RM550X |
| AIO COOLER | CORSAIR | Hydro Series™ H115i RGB PLATINUM |
| CASE | CORSAIR | Crystal Series 680X RGB ATX High Airflow Tempered Glass Smart Case |
| FAN | CORSAIR | LL140 * 2, LL120 * 4 |
| LED | CORSAIR | iCUE Lighting Node PRO RGB Lighting Controller |
| HEADSET | CORSAIR | VOID RGB ELITE USB Premium Gaming Headset with 7.1 Surround Sound |
| HEADSET STAND | CORSAIR | ST100 RGB Premium Headset Stand with 7.1 Surround Sound |
| KEYBOARD | CORSAIR | K70 RGB MK.2 Mechanical Gaming Keyboard — CHERRY® MX Brown |
| MOUSEPAD | CORSAIR | MM800 RGB POLARIS Gaming Mouse Pad |
| MOUSE | Apple | Magic Mouse 2 - Space Gray |
| TRACKPAD | Apple | Magic Trackpad 2 - Space Gray |
| LCD | LG | 29UM58-P |
| LCD | EIZO | FlexScan EV2450 |
| ACCESSORIES | Broadcom | BCM943602CS |
| ACCESSORIES | aibo | Bluetooth V4.0 微型藍芽傳輸器 |
| ACCESSORIES | TP-Link | TL-WN725N |

# Software
* macOS Mojave.app
* Unibeast 9.1.0
* Clover Configurator 5.2.1.0
* MultiBeast 11.0.1 Mojave Edition

# Install Step & Hint
* install Mojave.app into usb drive by Unibeast
* toggle the "fixshutdown" and change "darkwake" to 1
* add USBInjectAll.kext to /EFI/CLOVER/kexts/Other for solving No entry / Prohibited sign
* change bios setting, [refer this doc](https://github.com/Jian-Min-Huang/hackintosh/blob/master/doc/ASUS%20ROG%20STRIX%20Z370-G%20Hackintosh%20Guide%20mATX%20Build%20-%20Hackintosher.pdf)
* remove /EFI/drivers64/AptioMemoryFix-64.efi and add OsxAptioFix2Drv-64.efi for solving mojave install freezes with 2 minutes left
* usb drive boot install
  * -> restart
    * -> enter hard disk you install
      * keep install (can shutdown and connect network but no voice)
* override hard disk /EFI by usb drive /EFI
* install driver by Multibeast, [ref this image](https://github.com/Jian-Min-Huang/hackintosh/blob/master/img/MultiBeast-install.png?raw=true)
* add NoVPAJpeg.kext to /EFI/CLOVER/kexts/Other for solving jpg open
* you must remove hard disk in boot list when you reinstall hackintosh (No entry / Prohibited sign)
* dual hard disk with dual system
  * install separately by different boot (bios remove other hard disk)
    * at last, hackintosh hard disk has boot priority

# Checklist
* [x] shutdown
* [x] restart
* [x] sleep
* [x] audio
* [x] ethernet
* [x] wifi
* [x] bluetooth
* [ ] Right Frequency ?
* [ ] iMessage ?
* [ ] FaceTime ?
* [ ] iCloud ?

# Other Hint
* 黑鐵線
* 全模PSU
* 風扇插頭
* 4PIN插頭
* 3PIN插頭
* USB910插頭

# Reference
* https://www.tonymacx86.com/
* https://www.insanelymac.com/
* https://www.reddit.com/r/hackintosh/
* http://bbs.pcbeta.com/index.php?gid=86
* https://osx.cx/

![](https://github.com/Jian-Min-Huang/hackintosh/blob/master/img/pc.jpg?raw=true)
