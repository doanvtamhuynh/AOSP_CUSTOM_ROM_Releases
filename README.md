### This is the AOSP Custom ROM repository
---------------------------------------------------------------------------------
#### Flash Magisk for stock rom sargo
```
fastboot reboot fastboot 
fastboot flash boot boot_magisk-v28_sargo_stock_rom_android10.img
fastboot reboot
```
#### Update PIF using ADB
```
adb push /path/pif.json data/local/tmp
adb reboot
```
#### Update PIF using Android terminal
```
curl -L -o /data/local/tmp/pif.json https://raw.githubusercontent.com/doanvtamhuynh/AOSP_CUSTOM_ROM_Releases/master/pif.json
```
