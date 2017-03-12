PREREQUISITES To use this script make sure you have tor installed and running, and that you also have the pysocks module intalled.
Install tor, start it and check to make sure that its running
```
apt-get update
apt-get install tor
systemctl start tor.service
systemctl status tor.service
#Install the pysocks module
pip insall pysocks
```
PURPOSE This script is for stress testing websites against DOS attacks using the tor network, and is to be used for educational purposes only.

USAGE To run the script type:
```
python tolk.py url
```
(e.g. python tolk.py http://www.examplesite.com)

CREDITS GO TO http://www.sectorix.com and http://www.sendung.de
