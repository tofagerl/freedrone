freedrone
=========

This is my attempt at a standardized rc-script for NzbDrone on FreeBSD. 

* This uses a datafolder in the home-folder of the designated user. This can be changed, but do NOT put it in the NzbDrone folder, since this might be overwritten on updates. It's better to put it somewhere like /usr/local/nzbdrone/ or even in /etc/nzbdrone. 

* DO NOT RUN AS ROOT!

* Please send pull requests if you have any ideas to better this script. 

* Pid-file created since mono-apps has no awareness of the concept, and some system monitoring apps and other things need it.
