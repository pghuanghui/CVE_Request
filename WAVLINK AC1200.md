## 0x01 Vulnerability description

A vulnerability is in the 'live_mfg.shtml' page of the AERIAL X 1200M,Firmware package version M79X3.V5030.191012

Unauthorized users can obtain the key information of the router by visiting: 

```
http://xxx.xxx.xxx.xxx/live_mfg.shtml
```



## 0x02 Affected version

```
WAVLINK AERIAL X 1200M
```

## 0x03 Vulnerability

Under the live_mfg.shtml file, use the exec cmd function to execute the command

![image-20220517164702359](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20AC1200.assets/1.png)

## 0x04 PoC verification

![image-20220517171003252](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20AC1200.assets/2.png)


## 0x05 Acknowledgement
Penwei.Huang




