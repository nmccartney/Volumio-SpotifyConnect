May 18th 2017
	VOLUMIO SPOTIFY CONNECT 2 PLUGIN

This new version use librespot https://github.com/plietar/librespot
It is still in dev and some feature are missing.


Tested on :
- RPI 0 
- RPI B
- RPI B+
- RPI2
- SPARKY
- PINE64
- x86 laptop


IMPORTANT

- Requires a Premium or Family account

To install

- You only need to download volspotconnect2.zip. Take care to download the "raw" file, not only html from github...
- From Volumio UI choose "plugins" in setting, then "upload plugin" and select the file you have downloaded
Last changes

May 18th

- new librespot for armhf. Please wait for x86 and arm....

May 1st

add return libQ.resolve(); in index.js onVolumiostart

April 15th

- change error message when download requires package failed
- new librespot for armv6

April 14th

- new librespot with correction in protocol
- default volume is now about 30% instead of 100%

April 2nd

- Add auto restart service if hang

Mars 2nd

- generated proper startconnect.sh when enabling plugin

Mars 1st

- new librespot for armv6l

Febuary 28th

- update readme
- update remove.sh - chache size is now 64Mo

Febuary 27th

- option to share or no the device
- remove stream rate selector - default is now 320kbps 

Febuary 26th
- correct librespot x86
- correction to install on i686

Febuary 25th

-new librespot library with native multi-users
-support x86 arch
-cache written in /tmp

Febuary 19th

-cache is now written in /dev/shm to preserve sd card
-better global responsivness
-better handling multi users

Febuary 17th
correction when switching users

Febuary 16th

correction in remove.sh
correction volspotconnectpurgecache.service
correction onstart

Febuary 15th

New librespot libirary
Cache is now set to 64Mo with auto purge
  
Febuary 11th

New librespot version

January 25th

volumio is set on pause when start playing
add volspotconnect22.service

January 24th

fix drop when stop playing
allow multiple accounts

January 22th

crendetials autoremove when stop playing : discovery mode ok


January 21th

fix output device
try to autoremove credentials at stop
new work - first almost working plugin
remove x bit on service

January 20th

- First commit

Issues : 

Todo

- Add album art and working button in volumio UI
