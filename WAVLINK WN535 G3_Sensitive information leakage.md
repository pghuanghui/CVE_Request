## 0x01 Vulnerability description

An issue was discovered in Wavlink WN579G3,Firmware package version M35G3R.V5030.180927,affecting /cgi-bin/ExportAllSettings.sh where a crafted POST request returns the current configuration of the device, including the administrator password. No authentication is required. The attacker must perform a decryption step, but all decryption information is readily available.

## 0x02 Affected version

```
WAVLINK WN579 G3
```

## 0x03 Vulnerability

When viewing the /cgi-bin/ExportAllSettings.sh file, it was not properly authorized by the system.

![image-20220525112819333](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20WN579%20X3__Sensitive%20information%20leakage.assets/image-20220525112819333.png)

## 0x04 PoC verification

Directly construct the url link as:

```
http://xxx.xxx.xxx.xxx/cgi-bin/ExportAllSettings.sh
```

![image-20220624101602290](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20WN535%20G3_Sensitive%20information%20leakage.assets/image-20220624101602290.png)

![image-20220624101636507](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20WN535%20G3_Sensitive%20information%20leakage.assets/image-20220624101636507.png)

## 0x05 Acknowledgement

Penwei.Huang