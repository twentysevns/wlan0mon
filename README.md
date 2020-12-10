# Wlan0mon
*Enableling internal wifi "wlan0" to monitoring,
for Snapdragon Device ( android ).*

**Note!!!**
*Run as root* ```sudo su```

*If you run this scripts, and you try to enable wifi! 
Will can't be work! 
Because your internal driver **"wlan0"** run as monitor, 
so if you want to enable again and back to normal 
just* ```./stop.sh``` *his scripts.*


***( Installations )***

 ```sudo su```

 ```chmod +x stop.sh start.sh```

***( To run and stop )***
 
 ```./start.sh```

 ```./stop.sh```


***( Credit )***

*https://github.com/ripunk/wlan0mon*


*Getting random boot after* ```./start.sh```?
*Your firmware or kernel uncompatible with this maybe...
idk cuz i don't make it's scripts! :)* 
*but, dont worry after boot it doesnt make any change to your wifi.*
