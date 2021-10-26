![Tutorial](https://github.com/rafisyraf/Making-NAS-with-Raspberry-Pi-openmediavalult/blob/main/New%20Project%20(16).png)

# Making-NAS-with-Raspberry-Pi-openmediavalult
Im making a Raspberry Pi NAS using open media vault.

# THIS IS NOT FINISHED YET!!

*WHAT TO BUY*
- [x] Buy raspberry pi 3B+/4 ✅
- [x] Buy USB to SATA ✅
- [x] Buy 120GB of SSD ✅
- [x] Buy 8GB SDCARD ✅ 

## Tutorial:
Download Raspberry Pi imager 

![Tutorial](https://raw.githubusercontent.com/rafisyraf/Making-NAS-with-Raspberry-Pi-openmediavalult/main/RPI_intro-e1583228263677.png)

Click chose OS and click Raspberry pi OS (other) then click Raspbarry pi OS lite.
Plug in your sd card and then click chose storage and pick your sd card.
Then click write.

## 2: Installing the openmediavalut

![Tutorial](https://raw.githubusercontent.com/rafisyraf/Making-NAS-with-Raspberry-Pi-openmediavalult/main/pi-command-prompt.png)

Connect your keyboard, mouse and monitor.
Then power up your Raspberry pi.

Then login:
Username:pi
Password: raspberry

Then type:

sudo apt update

sudo apt upgrade -y

sudo rm -f /etc/systemd/network/99-default.link

sudo reboot

Then login again with Username:pi Password: raspberry

after that type this:
wget -O - https://github.com/OpenMediaVault-Plugin-Developers/installScript/raw/master/install | sudo bash
