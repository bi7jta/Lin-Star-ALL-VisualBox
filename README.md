Source from https://github.com/GhostBassist/Lin-Star-Bin ,Lin-Star-Bin, Lin-Star-Dash
  Thanks @GB7SL provide the first VMWare version.
  Thanks @W0CHP provide Dashboard.

# Preview

![image](https://github.com/bi7jta/Lin-Star-ALL-VisualBox/blob/main/screenshots/Pi-Star-Debian11-in-Visualbox6.png)

# Lin-Star , AMD64, x86 Pi-Star, WOCHP dashboard
Support VisualBox, VMWare, ESXi

# Indlucing project
https://github.com/bi7jta/Lin-Star-Bin_VisualBox

https://github.com/bi7jta/Lin-Star-Sbin_VisualBox

https://github.com/bi7jta/Lin-Star-Dash_VisualBox

# VDi download
Google device https://drive.google.com/drive/folders/1Pm9P77cIp1oWjWsbvPBK19d9b9OxYN6Q?usp=sharing

# Update logs
````
v1.0_build_20230505
Change Desktop to GNOME from KDE, fixed KDE desktop not work once export and import to new Windows10.

v1.0_build_20230504
Build with KDE desktop, all ready. This version has been discard.
````

````
Requirements:
OS: Windows10 +, MacOS x86
VisualBox: V7.0+  

Windows7+VisualBox V7 not work, can't start 
Can also work in V6.1 OSX, but recommend use V7.0+, with GNOME Desktop 

Assign IP and default newtork config, view run :
 ip a

2: enp0s8:   #VisualBox DHCP IP , you can visit ssh pi-star@192.168.56.101  
    inet 192.168.56.101/24 brd 192.168.56.255 scope global dynamic noprefixroute enp0s8

4: enp0s10:   
    inet 192.168.2.251/24 brd 192.168.2.255 scope global enp0s10 

Bridge LAN adapter static IP 192.168.2.251 , you can change it to your network in terminal, or set DHCP , just your Windows10/OSX use DHCP ,the VisualBox DHCP work ,otherwise set static IP:

sudo nano /etc/network/interfaces

Login: pi-star/raspberry,
root/raspberry (just support su root)

Build MMDVM repeater/hotspot easy!
````

## Reference :
Visuaobox 7.08 download : https://www.virtualbox.org/wiki/Downloads

Project and feedback issue: https://github.com/bi7jta/Lin-Star-ALL-VisualBox
## Follow me :
Github:  https://github.com/bi7jta

Facebook: https://www.facebook.com/winters.cn

YouTube: https://youtube.com/winters_huang

## Get MMDVM hardware and more support
https://www.bi7jta.org/wiki



