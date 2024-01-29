# XLX497
XLX497 Service Documentation &amp; Client Configurations
### DMR
  - Look at the [XLX497 Reflector](http://xlx497.k8oi.net/index.php?show=modules) and decide which Talk Group **TG** (4001, 4002, 4003, 4004) you wish to connect
#### Pi-Star
1.
#### DMR Programming/CodePlug
1.
---
### D-Star
  - Look at the [XLX497 Reflector](http://xlx497.k8oi.net/index.php?show=modules) and decide which **MODULE** (A, B, C, D) you wish to connect
#### Pi-Star
1. Log on the Pi-Star Admin Screen
2. Within the "D-Star Link Manager" Section
   ![Pi-Star](https://github.com/k8oi/XLX497/blob/main/XLX497%20D-Star%20Pi-Star%20Link%20Screenshot.png)
    1. Reflector: Select **XLX497**
    2. Module: Select the XLX module you wish to connect
    3. Ensure the **Link** option is selected
    4. Click \<Request Change\>
#### D-Star Radio
1. Ensure the URCALL field contains **CQCQCQ**
2. Key up and say hello.
---
### YSF
  - Look at the [XLX497 Reflector](http://xlx497.k8oi.net/index.php?show=modules) and decide which Digital Group **DG** (10, 11, 12, 13) you wish to connect
#### Pi-Star
1. Log on the Pi-Star Admin Screen
2. Within the "YSF Link Manager" Section
    1. Reflector: Select **YSF22102 - XLX497 - XLXreflector**
    2. Ensure the **Link** option is selected
    3. Click \<Request Change\>
#### YSF Radio
1. Change the **DG-ID TX** to the **DG** you wish to connect.
2. Ensure the **DG-ID RX** is set to 0 (zero).
3. Key up and you're connected to the **DG**
