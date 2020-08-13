# Fastboot Images For Realme Devices
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Facervenky%2Frealmefastboot)](https://hits.seeyoufarm.com) [![Hits](https://img.shields.io/github/issues-closed/acervenky/realmefastboot)](https://github.com/acervenky/realmefastboot/issues)


| Device | Region | Firmware Version | Link |
| :-: | :-: | :-: | :-: | 
| Realme 1 | IN | C49 | [AFH](https://www.androidfilehost.com/?fid=12420606652095400852) |
| Realme 3 Pro | IN | C02 | [AFH](https://androidfilehost.com/?fid=4349826312261729069) |
| Realme 5 Pro | IN | A11 | [AFH](https://androidfilehost.com/?fid=4349826312261604056) |
| Realme 5s | IN | C53 | [AFH](https://www.androidfilehost.com/?fid=8889791610682914173) |
| Realme 6 Pro | IN | A29 | [AFH](https://www.androidfilehost.com/?fid=8889791610682914150) |
| Realme C11 | IN | A67 | [AFH](https://www.androidfilehost.com/?fid=8889791610682913185) |
| Realme Q | CN | A06 | [AFH](https://androidfilehost.com/?fid=1899786940962607920) |
| Realme XT | IN | A10 | [AFH](https://androidfilehost.com/?fid=1899786940962606272) |
| Realme XT | RU | C04 | [AFH](https://www.androidfilehost.com/?fid=8889791610682911879) |
| Realme X2 | CN | A14 | [AFH](https://androidfilehost.com/?fid=4349826312261730515) |
| Realme X2 | EU | A18 | [AFH](https://www.androidfilehost.com/?fid=4349826312261732159) |
| Realme X2 | IN | A18 | [AFH](https://androidfilehost.com/?fid=4349826312261728724) |
| Realme X2 Pro | CN | A11 | [AFH](https://androidfilehost.com/?fid=4349826312261628809) |
| Realme X2 Pro | EU | A06 | [AFH](https://androidfilehost.com/?fid=4349826312261642076) |
| Realme X2 Pro | IN | A07 | [AFH](https://androidfilehost.com/?fid=4349826312261679551) |
| Realme X2 Pro | IN | A09 | [AFH](https://www.androidfilehost.com/?fid=4349826312261728685) |
| Realme X3 SuperZoom | IN | A33 | [AFH](https://www.androidfilehost.com/?fid=8889791610682898218) |
| Realme X50 | CN | A08 | [AFH](https://androidfilehost.com/?fid=4349826312261729427) |
| Realme X50 Pro | IN | A29 | [AFH](https://www.androidfilehost.com/?fid=8889791610682911838) |
| Realme X50 Pro | EU | A28 | [AFH](https://www.androidfilehost.com/?fid=8889791610682911854) |


If your device is not listed, please follow this guide :\
[![](http://img.youtube.com/vi/WIPsJqIXrmk/0.jpg)](http://www.youtube.com/watch?v=WIPsJqIXrmk "")


# Steps To Flash 
- Download Latest Fastboot Files From Google

- Open cmd in the fastboot folder

- Boot device in fastboot mode

Use following commands to flash the images :
```
fastboot flash boot boot.img

fastboot flash system system.img

fastboot flash vbmeta vbmeta.img

fastboot flash vendor vendor.img
```

# Boot Partition Damaged Error After Root
Use the following command while in fastboot mode :
```
fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img
```
