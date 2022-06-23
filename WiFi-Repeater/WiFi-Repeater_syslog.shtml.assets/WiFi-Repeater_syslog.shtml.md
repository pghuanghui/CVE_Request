## 0x01 Vulnerability description

A vulnerability is in the 'syslog.shtml' page of the Wavlink-WiFi-Repeater,Firmware package version RPTA2-77W.M4300.01.GD.2017Sep19,Attackers can use this page to configure various functions of the repeater.

Unauthorized users can obtain the key information of the router by visiting: 

```
http://xxx.xxx.xxx.xxx/syslog.shtml
```

## 0x02 Affected version

```
Wavlink-WiFi-Repeater
```

## 0x03 Vulnerability

When the router is running, all the operations of the user are stored in the syslog.shtml page, and the identity verification process is not performed

## 0x04 PoC verification

![image-20220623150043519](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_syslog.shtml.assets/image-20220623150043519.png)

![(wavlink-WiFi-Repeater_syslog.shtml.assets/image-20220623145655255.png)

![image-20220623145938144](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_syslog.shtml.assets/image-20220623145938144.png)

## 0x05 Acknowledgement

Penwei.Huang