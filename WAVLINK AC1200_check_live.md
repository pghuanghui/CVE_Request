## 0x01 Vulnerability description

A vulnerability is in the 'live_check.shtml' page of the AERIAL X 1200M,Firmware package version M79X3.V5030.180719

Unauthorized users can obtain the key information of the router by visiting: 

```
http://xxx.xxx.xxx.xxx/live_check.shtml
```

## 0x02 Affected version

```
WAVLINK AERIAL X 1200M
```

## 0x03 Vulnerability

Under the live_check.shtml file, use the exec cmd function to execute the command

![image-20220518145059172](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20AC1200_check_live.assets/image-20220518145059172.png)

## 0x04 PoC verification

![image-20220518145211411](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20AC1200_check_live.assets/image-20220518145211411.png)

![image-20220518145246880](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20AC1200_check_live.assets/image-20220518145246880.png)

![image-20220518145313942](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20AC1200_check_live.assets/image-20220518145313942.png)

In the live_check.shtml interface, it contains various information of the router, such as: firmware version, MAC address, etc., and even information such as the running process of the router.
## 0x05 Acknowledgement
Penwei.Huang
