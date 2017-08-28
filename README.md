# vcgencmd-tocentos-raspberrypi
Customized fork from original repository

Cent OS on Raspberry pi

```
git clone https://github.com/corokada/vcgencmd-tocentos-raspberrypi
cd vcgencmd-tocentos-raspberrypi
sh tocentos.sh
```

```
wget -O /bin/vcgencmd https://github.com/raspberrypi/firmware/raw/master/hardfp/opt/vc/bin/vcgencmd
wget -O /lib/libvchiq_arm.so https://github.com/raspberrypi/firmware/blob/master/hardfp/opt/vc/lib/libvchiq_arm.so
wget -O /lib/libvcos.so https://github.com/raspberrypi/firmware/blob/master/hardfp/opt/vc/lib/libvcos.so
chmod +x /bin/vcgencmd
```
