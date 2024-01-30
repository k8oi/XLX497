# BlueDV Setup for XLX497 Access
**Purpose:** Provide a basic configuration and linking process from [BlueDV]() to the XLX497 Reflector for each digital radio type: DMR/D-Star/YSF
### BlueDV Setup & Configuration

[Current XLX497 Reflector Modules List](http://xlx497.k8oi.net/index.php?show=modules)

![XLX497 Module List](https://github.com/k8oi/XLX497/blob/main/XLX497%20Module%20List%20Screenshot.png)
---
### DMR
  - Look at the [XLX497 Reflector Modules List](http://xlx497.k8oi.net/index.php?show=modules) and decide which Talk Group **TG** (4001, 4002, 4003, 4004) you wish to connect
#### Pi-Star
1. Log on the Pi-Star Configuration Screen
2. Within the "DMR Configuration" Section
![DMR Pi-Star Configuration](https://github.com/k8oi/XLX497/blob/main/XLX497%20DMR%20Pi-Star%20Configuration%20Settings.png)
3. Set the following:
  - DMR Master: DMRGateway
  - XLX Master: XLX_497
  - XLX Startup Module: A
  - XLX Master Enable: On/Enabled
  - DMR Color Code: 1
  - DMR EmbeddedLCOnly: On/Enabled
  - DMR DumpTAData: On/Enabled
4. Click "Apply Changes"

#### DMR Programming/CodePlug
1. Modify ayour codeplug to include the following 5 Contacts

| Name | CallID | CallType | XLX497 Module Number |
| ---------- | :-------: | :---: | :---: |
| XLX497 CQ | 6 | Group | |
| XLX497 A | 64001 | Private | 4001 |
| XLX497 B | 64002 | Private | 4002 |
| XLX497 C | 64003 | Private | 4003 |
| XLX497 D | 64004 | Private | 4004 |
