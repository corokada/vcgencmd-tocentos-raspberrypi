# vcgencmd-tocentos-raspberrypi
Customized fork from original repository

Cent OS on Raspberry pi

```
git clone https://github.com/corokada/vcgencmd-tocentos-raspberrypi
cd vcgencmd-tocentos-raspberrypi
sh tocentos.sh
```

official
```
wget -O /bin/vcgencmd https://raw.githubusercontent.com/raspberrypi/firmware/master/hardfp/opt/vc/bin/vcgencmd
wget -O /lib/libvchiq_arm.so https://raw.githubusercontent.com/raspberrypi/firmware/master/hardfp/opt/vc/lib/libvchiq_arm.so
wget -O /lib/libvcos.so https://raw.githubusercontent.com/raspberrypi/firmware/master/hardfp/opt/vc/lib/libvcos.so
chmod +x /bin/vcgencmd
```
fork
```
wget -O /bin/vcgencmd https://raw.githubusercontent.com/corokada/vcgencmd-tocentos-raspberrypi/master/hardfp/opt/vc/bin/vcgencmd
wget -O /lib/libvchiq_arm.so https://raw.githubusercontent.com/corokada/vcgencmd-tocentos-raspberrypi/master/hardfp/opt/vc/lib/libvchiq_arm.so
wget -O /lib/libvcos.so https://raw.githubusercontent.com/corokada/vcgencmd-tocentos-raspberrypi/master/hardfp/opt/vc/lib/libvcos.so
chmod +x /bin/vcgencmd
```

一覧
vcgencmd commands
CPU温度
vcgencmd measure_temp
CPU周波数
vcgencmd measure_clock arm
電圧
vcgencmd measure_volts

他　http://elinux.org/RPI_vcgencmd_usage
