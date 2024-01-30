# BlueDV Setup for XLX497 Access
**Purpose:** Provide a basic configuration and linking process from [BlueDV](https://www.pa7lim.nl/bluedv/) to the XLX497 Reflector for each digital radio type: DMR/D-Star/YSF

[Current XLX497 Reflector Modules List](http://xlx497.k8oi.net/index.php?show=modules)
---
### BlueDV Setup & Configuration

![BlueDV Configuration Screen](https://github.com/k8oi/XLX497/blob/main/BlueDV_Images/BlueDV%20General%20Configuration%20Screen.png)

---
### DMR
  - Look at the [XLX497 Reflector Modules List](http://xlx497.k8oi.net/index.php?show=modules) and decide which Talk Group **TG** (4001, 4002, 4003, 4004) you wish to connect
#### BlueDV
1. Select DMR button (bottom right)
2. Select AMBE tab (if not already selected)
3. Enter the TG # you wish to connect. For example: 4001 for Module A
4. Select P for Private Call
   
![BlueDV TG P](https://github.com/k8oi/XLX497/blob/main/BlueDV_Images/DMR%20Group%204001.png)

5. Press PTT once - this "links" BlueDV to the module
6. Enter the number 6 (six) in the TG Box
7. Select G for Group Call

![BlueDV TG G](https://github.com/k8oi/XLX497/blob/main/BlueDV_Images/DMR%20Group%206.png)

8. You are now able to talk on XLX497 TG 4001 - Module A
---
### D-Star
  - Look at the [XLX497 Reflector Modules List](http://xlx497.k8oi.net/index.php?show=modules) and decide which **MODULE** (A, B, C, D) you wish to connect
#### BlueDV
1. Log on the Pi-Star Admin Screen
2. Within the "D-Star Link Manager" Section
![D-Star Pi-Star](https://github.com/k8oi/XLX497/blob/main/Pi-Star_Images/XLX497%20D-Star%20Pi-Star%20Link%20Screenshot.png)
    1. Reflector: Select **XLX497**
    2. Module: Select the XLX module you wish to connect
    3. Ensure the **Link** option is selected
    4. Click \<Request Change\>

---
### YSF
  - Look at the [XLX497 Reflector Modules List](http://xlx497.k8oi.net/index.php?show=modules) and decide which Digital Group **DG** (10, 11, 12, 13) you wish to connect
#### Pi-Star
