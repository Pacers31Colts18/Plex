##Initial Configuration
1.	Install Ubuntu VM on Proxmox
2.	Run sudo apt-get update && sudo apt-get upgrade

##Plex Install
How to Install Plex Media Server on Ubuntu 20.04 – LinuxWays
wget https://downloads.plex.tv/plex-media-server-new/1.20.4.3517-ab5e1197c/debian/plexmediaserver_1.20.4.3517-ab5e1197c_amd64.deb
sudo apt install ./plexmediaserver_1.20.4.3517-ab5e1197c_amd64.deb
Configure the Firewall
Install Plex Media Server on Ubuntu | Delft Stack
Mount USB Drive
Detect and mount USB devices in Linux from console | Simple IT 🤘 Rocks
 
 
sudo mkdir /mnt/wd10tb
sudo mount -t auto /dev/sdb1 /mnt/wd10tb
UUID="344A76D04A768DFC"
 
##NZBGet
https://www.htpcguides.com/install-latest-nzbget-on-ubuntu-15-x-with-easy-updates
	Change Username and Password
•	Settings >  Security
NewsServers
•	Eweka
•	NewsDemon
Change Paths
•	Settings > Paths
o	MainDir: /mnt/wd10tb/Usenet-Linux/downloads
o	DestDir: /mnt/wd10tb/Usenet-Linux/completed
o	InterDir: /mnt/wd10tb/Usenet-Linux/intermediate
o	NZBDir: /mnt/wd10tb/Usenet-Linux/nzb

##Sonarr
https://sonarr.tv/#downloads-v3-linux
Change username and group to jloveless123 during installation
Add Download Clients (NZBGet)
Add Indexers (Newznab > NZBGeek)
•	Get information from nzbgeek.info

##Radarr
https://wiki.servarr.com/install-script
	Change username and group to jloveless123

##Bazarr
https://wiki.bazarr.media/Getting-Started/Installation/Linux/linux/#ubuntu-debian-install-requirements-with
https://wiki.bazarr.media/Getting-Started/AUtoStart/Linux/linux

Providers: OpenSubtitles.org

