## 0x01 Vulnerability description

A vulnerability is in the 'tftp.txt' page of the Wavlink-WiFi-Repeater,Firmware package version RPTA2-77W.M4300.01.GD.2017Sep19,The attacker can access the constructed page to obtain the telnet account password.

Unauthorized users can obtain the key information of the router by visiting: 

```
http://xxx.xxx.xxx.xxx/tftp.txt
```

## 0x02 Affected version

```
Wavlink-WiFi-Repeater
```

## 0x03 Vulnerability

The txt text does not set reasonable access rights.

## 0x04 PoC verification

![image-20220623150043519](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_syslog.shtml.assets/image-20220623150043519.png)

![image-20220623152150836](https://github.com/pghuanghui/CVE_Request/raw/main/WiFi-Repeater/WiFi-Repeater_syslog.shtml.assets/WiFi-Repeater_tftp/WiFi-Repeater_tftp.assets/image-20220623152150836.png)

## 0x05 Acknowledgement

Penwei.Huang