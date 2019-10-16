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
| RADIATOR | CORSAIR | Hydro Series™ H115i RGB PLATINUM |
| CASE | CORSAIR | Crystal Series 680X RGB ATX High Airflow Tempered Glass Smart Case |
| FAN | CORSAIR | LL140 * 2, LL120 * 4 |
| LED | CORSAIR | iCUE Lighting Node PRO RGB Lighting Controller |
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

=== Tools
* Install macOS Mojave.app
* Unibeast 9.1.0
* Clover Configurator 5.2.1.0
* MultiBeast 11.0.1 Mojave Edition

=== Install Step & Hint
* 按照 Unibeast 步驟安裝至隨身碟
* fixshutdown打勾, darkwake=1
* add USBInjectAll.kext to /EFI/CLOVER/kexts/Other for solving No entry / Prohibited sign
* 調整 bios, 請參考 https://github.com/Jian-Min-Huang/tech-note/blob/master/doc/ASUS%20ROG%20STRIX%20Z370-G%20Hackintosh%20Guide%20mATX%20Build%20-%20Hackintosher.pdf[bios]
* remove /EFI/drivers64/AptioMemoryFix-64.efi, add OsxAptioFix2Drv-64.efi, 請 google mojave install freezes with 2 minutes left
* 隨身碟開機安裝 -&gt; 重開 -&gt; 進入硬碟 -&gt; 繼續安裝
* 這個狀況 可關機 有網路 沒聲音
* 接下來把隨身碟的/EFI蓋掉硬碟的/EFI
* 按照 Multibeast 的步驟安裝需要的驅動

image::https://github.com/Jian-Min-Huang/tech-note/blob/master/img/MultiBeast%20Install.png[multibeast]

* NoVPAJpeg fix jpg open
* 重灌一定要在 Bios Boot 把上一個硬碟拿掉, 不然會禁止符號
* 雙硬碟雙系統就分開裝但是最後用mac那顆優先 Boot 就好

=== Checklist
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

=== Other Hint
* 黑鐵線
* 全模
* 風扇插頭
* 4PIN插頭
* 3PIN插頭
* USB910插頭

=== Reference
* Tonymacx86
* InsanelyMac
* Reddit Hackintosh
* 遠景論壇
* https://osx.cx/

![](https://github.com/Jian-Min-Huang/hackintosh/blob/master/img/pc.jpg?raw=true)
