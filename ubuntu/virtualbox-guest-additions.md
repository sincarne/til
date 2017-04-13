In the terminal:
* run `sudo apt update`
* run `sudo apt upgrade`
* install the required packages with `sudo apt-get install build-essential module-assistant`
* run `sudo m-a prepare` to ensure the system is ready to compile the necessary extensions
* click on Devices → Install Guest Additions… to mount the cd
  * if running under Ubuntu Server (or any system without automounting ability), mount the CD with `sudo mount /dev/cdrom /media/cdrom`
* run `sudo sh /media/cdrom/VBoxLinuxAdditions.run`
