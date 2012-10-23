pppd configuration files for mobile broadbands
==============================================
http://ppp.samba.org/

Most of the stuff is "stolen" from https://wiki.archlinux.org/index.php/3G_and_GPRS_modems_with_pppd
(Arch Linux ftw!)

remember to do symbolic links
e.g. in /etc/ppp/ -folder:

ln -s peers/mobile-noauth.wait peers/provider
ln -s chatscripts/dna.apn chatscript/apn
ln -s chatscripts/mode.NONE chatscript/mode
ln -s chatscripts/pin.NONE chatscript/pin
