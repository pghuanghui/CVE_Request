## 0x01 Vulnerability description

A vulnerability is in the 'live_mfg.shtml' page of the WAVLINK WN535 G3,Firmware package version M35G3R.V5030.180927

Unauthorized users can obtain the key information of the router by visiting: 

```
http://xxx.xxx.xxx.xxx/live_mfg.shtml
```

## 0x02 Affected version

```
WAVLINK WN535 G3
```

## 0x03 Vulnerability

Under the live_mfg.shtml file, use the exec cmd function to execute the command

![image-20220523171655790]([WAVLINK WN535 G3__live_mfg.assets/image-20220523171655790-16532974334661.png](https://github.com/pghuanghui/CVE_Request/raw/main/WAVLINK%20WN535%20G3__live_mfg.assets/image-20220523171655790.png))

## 0x04 PoC verification

![image-20220523171850455](WAVLINK WN535 G3__live_mfg.assets/image-20220523171850455.png)

## 0x05 	Acknowledgement

Peiwen.Huang
