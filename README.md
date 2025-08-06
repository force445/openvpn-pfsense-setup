# OpenVPN setup for Pfsense

## Requirements
- Proxmox
- Pfsense iso image
- Network setup

## Create Pfsense server
1. Click the Create VM button on the upper right corner.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/Screenshot%202568-08-06%20at%2011.30.31.png)


2. Name the VM and choose iso image and customize setting as you want.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/Screenshot%202568-08-06%20at%2011.53.02.png)
![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/Screenshot%202568-08-06%20at%2011.54.30.png)


3. After finish the configuration click on finish button and start the VM.


![Alt text](http://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/Screenshot%202568-08-06%20at%2011.55.55.png)

## Pfsense setup
1. After start VM press enter accept the agreement to begin setup process.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image.png)


2. Choose Install to install pfsense.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy.png)


3. Choose Continue with default keymap.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%202.png)


4. Choose Auto (UFS) BIOS.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%203.png)


5. After finish installing choose No and reboot to finish pfsense installation.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%204.png)
![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%205.png)


6. Choose n to setup VLANs later.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%206.png)

7. Choose vtnet0 for WAN and the enter.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%207.png)
![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%208.png)


8. Choose y to proceed.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%209.png)


9. Use the IPv4 to enter Pfsense web then enter the pfsense using default username and password.



![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2010.png)
![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2011.png)


10. Leave everything to default unless you want more customization.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2012.png)
![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2013.png)
![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2014.png)


11. Check block bogon networks out and then click next.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2015.png)


12. After finish check for updates to upgrade pfsense into newer version and wait until the update is finish.


![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2016.png)
![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2017.png)
![Alt text](https://github.com/force445/openvpn-pfsense-setup/blob/main/pictures/image%20copy%2018.png)


## OpenVPN setup

1. 