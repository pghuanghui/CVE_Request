## 0x01 Vulnerability description

A vulnerability is in the 'messages.txt'page of the WAVLINK WN579 X3,Firmware package versionM79X3.V5030.191012/M79X3.V5030.191012

Unauthorized users can obtain the key information of the router by visiting: 

```
http://xxx.xxx.xxx.xxx/messages.txt
```

## 0x02 Affected version

```
WAVLINK WN579 X3
```

## 0x03 Vulnerability

When the router is running, all the operations of the user are stored in the messages.txt text, and the identity verification process is not performed.

## 0x04 PoC verification

![image-20220623114715759](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20WN579%20X3__messages.assets/image-20220623114715759.png)

## 0x05 Acknowledgement

Penwei.Huang