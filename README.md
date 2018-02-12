lazycast: A Simple Miracast Receiver for Raspberry Pi

# Description:
lazycast is a simple Miracast receiver. It was originally targeted Raspberry Pi (as display) and Windows 8.1/10 (as source), but it should work with other linux distro and Miracast sources, too. lazycast, in general, does not require recompilation of wpa_supplicant to provide p2p capability. 

# Require package: 
net-tools python udhcpd vlc

Note: udhcpd is a DHCP server for Ubuntu and Debian.
Note: use omxplayer on Raspberry Pi for HW acceleration

# Usage:

Run
./all.sh
to initiate lazycast receiver. Wait until the "The display is ready" message.
Then, search for a Miracast screen named "lazycast" on the device you want to cast. Use the pin number below "The display is ready" message if the device is asking WPS pin number.

# Known issue:
latency
