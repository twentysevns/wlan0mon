# Wlan0mon
*Enableling internal wifi **"wlan0"** to monitoring,
for Qualcomm Device ( android ).*
#
#
***( Important! )***

- *Run as root* ```sudo su```

- *If you run this scripts and you try to use wifi! 
Will can't be work! 
Because your internal driver **"wlan0"** run as monitor, 
so if you want to enable again and back to normal 
just* ```./stopwlan0``` *his scripts.*
#
***( Installations )***

1. ```sudo su```
2. ```cd wlan0mon```
3. ```chmod +x stopwlan0 startwlan0```
#
***( To run and stop )***
 
- ```./startwlan0```
- ```./stopwlan0``` 
#
***( Credit )***

*https://github.com/ripunk/wlan0mon*
#
***( Little Problem )***

- *Getting random boot after* ```./startwlan0```?
*Your firmware or kernel uncompatibled maybe...
idk cuz i don't make it's scripts! :)* 
*but, dont worry after boot it, doesnt make any change to your wifi.*
