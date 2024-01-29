# XLX497
### XLX497 Module List
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

2. Program your radio with your updated code plug.
#### Linking & Calling CQ
1. Select the Module you wish to connect on your radio: Example XLX497 A would be Module 4001
2. Key the radio - this "links" the Pi-Star to the Module
3. Select the XLX497 CW channel on your radio
4. Key the radio and call CQ!
   
---
### D-Star
  - Look at the [XLX497 Reflector Modules List](http://xlx497.k8oi.net/index.php?show=modules) and decide which **MODULE** (A, B, C, D) you wish to connect
#### Pi-Star
1. Log on the Pi-Star Admin Screen
2. Within the "D-Star Link Manager" Section
![D-Star Pi-Star](https://github.com/k8oi/XLX497/blob/main/XLX497%20D-Star%20Pi-Star%20Link%20Screenshot.png)
    1. Reflector: Select **XLX497**
    2. Module: Select the XLX module you wish to connect
    3. Ensure the **Link** option is selected
    4. Click \<Request Change\>
#### D-Star Radio
1. Ensure the URCALL field contains **CQCQCQ**
2. Key up and say hello.
---
### YSF
  - Look at the [XLX497 Reflector Modules List](http://xlx497.k8oi.net/index.php?show=modules) and decide which Digital Group **DG** (10, 11, 12, 13) you wish to connect
#### Pi-Star
1. Log on the Pi-Star Admin Screen
2. Within the "YSF Link Manager" Section
![YSF Pi-Star](https://github.com/k8oi/XLX497/blob/main/XLX497%20YSF%20Pi-Star%20Link%20Screen%20Configuration.png)
    1. Reflector: Select **YSF22102 - XLX497 - XLXreflector**
    2. Ensure the **Link** option is selected
    3. Click \<Request Change\>
#### YSF Radio
1. Change the **DG-ID TX** to the **DG** you wish to connect.
2. Ensure the **DG-ID RX** is set to 0 (zero).
![YSF Radio DG-ID](https://github.com/k8oi/XLX497/blob/main/YSF%20Radio%20-%20Set%20DG-ID%20TX.png)
4. Key up and you're connected to the **DG**
