## 0x01 Vulnerability description

A vulnerability is in the 'mb_wifibasic.shtml' page of the Wavlink-WiFi-Repeater,Firmware package version RPTA2-77W.M4300.01.GD.2017Sep19,Visit the constructed page to get the Wi-Fi Basic Setting, and you can set the WiFi at the same time.

Unauthorized users can obtain the key information of the router by visiting: 

```
http://xxx.xxx.xxx.xxx/mb_wifibasic.shtml
```

## 0x02 Affected version

```
Wavlink-WiFi-Repeater
```

## 0x03 Vulnerability

This page does not have access permissions set

## 0x04 PoC verification

![image-20220623150043519](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_syslog.shtml.assets/image-20220623150043519.png)

![image-20220623153613992](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_mb_wifibasic.assets/image-20220623153613992.png)

## 0x05 Acknowledgement

Penwei.Huang