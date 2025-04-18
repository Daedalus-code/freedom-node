
# Freedom-Node  

### Spin up a Freedom node!  
Raspberry pi + [Raspberry Pi OS  ](https://www.raspberrypi.com/software/)  

``sudo apt-get install git -y``  

``cd && git clone https://github.com/Daedalus-code/Freedom-node.git``  

``bash freedom-node/include/install``  

### Setup rc.local for dashbord at boot

edit rc.local  
``sudo nano /etc/rc.local``  

Change 'pi' user if needed, put this before exit, not after!  
``sleep 10 && sudo -u pi bash /usr/local/bin/dash &``  

Save with ctrl+o and reboot  

### Trade FreedomCoin (FREED) on XeggeX, NonKYC

[XeggeX](https://xeggex.com?ref=650e9399625501b3b53b1172)  
[NonKYC](https://nonkyc.io?ref=66a730caaee63aa82784b011)  
