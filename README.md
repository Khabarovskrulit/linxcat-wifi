# linxcat-wifi
Arch-Based User-Friendly Wi-Fi Connect utility.

### Installing
1. Iwctl (lwd paketinde bulunan), dialog ve dhclient bağımlılıklarının yüklü olduğundan emin olun.
```
[voitonic@cryctal ~]$ ls /usr/bin | grep -P 'dialog|iwctl|dhclient'
cinnamon-file-dialog
cinnamon-screensaver-lock-dialog
dhclient
dhclient-script
dialog
dialog-config
gdialog
iwctl
knewstuff-dialog
xlet-about-dialog
```
Eğer yoksa, o zaman bir komutla kurarız :
```
$pacman -S dialog iwd dhclient
```
2. dosyayı root altından kopyalarız
```
$ sudo cp ~/linxcat-wifi/linxcat-wifi /usr/bin && chmod u+x /usr/bin/linxcat-wifi
```
3. Sadece root altından çalıştır.


