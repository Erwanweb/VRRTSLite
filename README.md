# VRRTSLite
VRRTSLite

install :

cd ~/domoticz/plugins

mkdir VRRTSLite

sudo apt-get update

sudo apt-get install git

git clone https://github.com/Erwanweb/VRRTSLite.git VRRTSLite

cd VRRTSLite

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart

Upgrade :

cd ~/domoticz/plugins/VRRTSLite

git reset --hard

git pull --force

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart
