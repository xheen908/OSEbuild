# OSEbuild Application Beta

*Compatible with Android 4.0.3 and above.*

---
#### cam.apk 
*Version:* ***8.4*** "remove old"
*"No graphics interface: 127.0.0.1:8888"*
```
Enable storage access from Android 6.0
Android /Settings/Apps/OSCam/Permissions/Storage "and enable"
```
#### Cam installation:

```sh
cp /storage/OSEbuild/installation/installation/"oscam"-"CPU/ABI".zip"
```
```
android.permission.INTERNET
android.permission.RECEIVE_BOOT_COMPLETED
android.permission.WRITE_EXTERNAL_STORAGE
android.permission.READ_EXTERNAL_STORAGE
```
---
#### pcsc.apk
*Version:* ***8.3.15***
+ [PCSC-Lite](https://pcsclite.alioth.debian.org/pcsclite.html "PCSC-Lite")
+ [CCID driver](https://pcsclite.alioth.debian.org/ccid.html "CCID driver")
+ [libusb](https://github.com/libusb/libusb/wiki "libusb")
```
android.permission.WRITE_EXTERNAL_STORAGE
android.permission.READ_EXTERNAL_STORAGE
android.permission.RECEIVE_BOOT_COMPLETED
android.permission.ACCESS_SUPERUSER
```

