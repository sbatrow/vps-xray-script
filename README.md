# vps-xray-script

* UPDATE 8/09/2021 


![logo](https://telegra.ph/file/7b4030d597e597aa45a4b.jpg)


Using Xray-Script you can experience a high speed network connection / Low ping / Full stable connection ...

Xray-Script එක Use කරල ඔයාට High speed Network Connection එකක් / Low ping / Full stable Connection එකක් අත්විදින්න පුලුවන් ...


Manage Scrip

## :heavy_exclamation_mark: Requirements

* Vps with Ubuntu 20.04 or Ubuntu-latest OS.
* A UUID (Generate a UUID via V2rayN or http://uuidgenerator.net).
* Use xray-nodomain script to connect directly from IP without using DNS.

* Ubuntu 20.04 or Ubuntu-latest Os එක සහිත Vps එකක්.
* UUID එකක් (V2rayN මගින් හෝ http://uuidgenerator.net මගින් UUID එකක් Genarate කරගන්න).
* DNS use නොකර Ip එකෙන් direct connect කරගන්න xray-nodomain ස්ක්‍රිප්ට් එක භාවිතා කරන්න.

------------------------------------------
## :book: Installation - Without DNS

1)
```
apt-get update -y && apt-get upgrade -y
```
2)
```
sudo reboot (To restart after the update)
```
4)
```
sudo git clone https://github.com/sbatrow/vps-xray-script
```
5)
```
cd vps-xray-script
```
6)
```
sudo chmod 777 xray-nodomain.sh
```
7)
```
sudo ./xray-nodomain.sh
```
------------------------------------------

## :book: How To Connect

1) If you are an Android user, download V2rayNG (
https://github.com/2dust/v2rayNG)

2) If you are a Windows user, download V2rayN or Netch software

1)Android User කෙනෙක්නම් V2rayNG Download කරගන්න (
https://github.com/2dust/v2rayNG)

2)Windows User කෙනෙක්නම් V2rayN හො Netch Software දෙක Download කරගන්න (https://bit.ly/3jONhAl)

![logo](https://telegra.ph/file/372eb568ce7a7776aa8c4.jpg)

* AlterId   =   4

* Http Port =  80

* Xtls port = 443

## :book: Unistallation (Remove xray-core and all modified config files from the server) *will not remove BBR

1) sudo rm  -rf  ~/bash-xray-script

2) sudo git clone https://github.com/sbatrow/vps-xray-script

3) cd vps-xray-script

4) sudo chmod 777 remove-xray.sh

5) sudo ./remove-xray.sh

## :octocat: Credits

1. https://github.com/teddysun - BBR autoscript
2. Team Rezoth - Contributor

☆😁 https://t.me/batrow_support 😁☆
