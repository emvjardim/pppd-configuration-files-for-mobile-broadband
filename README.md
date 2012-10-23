pppd configuration files for mobile broadbands
==============================================
http://ppp.samba.org/

Most of the stuff is "stolen" from https://wiki.archlinux.org/index.php/3G_and_GPRS_modems_with_pppd
(Arch Linux ftw!)


* cd /etc/ppp/
* git clone https://github.com/saturation/pppd-configure-files-for-mobile-broadband.git .
* change settings if needed
* and remember to do symbolic links e.g. 

ln -s peers/mobile-noauth.wait peers/provider

ln -s chatscripts/dna.apn chatscript/apn

ln -s chatscripts/mode.NONE chatscript/mode

ln -s chatscripts/pin.NONE chatscript/pin


(These are the settings that I am using on Raspberry Pi with combination of Arch Linux, Nokia CS-17 internet stick and DNA as ISP)
