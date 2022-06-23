## 0x01 Vulnerability description

A vulnerability is in the 'tftp.txt' page of the Wavlink-WiFi-Repeater,Firmware package version RPTA2-77W.M4300.01.GD.2017Sep19,By constructing this link, you can get the ftp configuration file.

Unauthorized users can obtain the key information of the router by visiting: 

```
http://xxx.xxx.xxx.xxx/Tftpd32.ini
```

## 0x02 Affected version

```
Wavlink-WiFi-Repeater
```

## 0x03 Vulnerability

The ftp configuration file does not have reasonable access rights settings.

## 0x04 PoC verification

![image-20220623150043519](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_syslog.shtml.assets/image-20220623150043519.png)

![image-20220623155041419](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_Tftpd32.assets/image-20220623155041419.png)

![image-20220623155122557](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_Tftpd32.assets/image-20220623155122557.png)

## 0x05 Acknowledgement

Penwei.Huang