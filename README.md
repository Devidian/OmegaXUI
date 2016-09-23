# OmegaXUI
7 Days To Die XUI by Devidian

Some additions to the basic UI, adding food, water, xp bars and Temperature / Elevation level.
Also adds an compass center indicator.

## Screenshot
![alt text](http://xui.omega-zirkel.de/screen002.jpg "XUI Screenshot #2")

## Installation Information
The current master is ONLY for Alpha 15, dont try to use with a lower Alpha version.
### Linux Dedicated Server

Connect to your server via ssh and go to your Data folder. This for example is when you use allocs fixes:

```
cd /home/sdtd/engine/Data/
git clone https://github.com/Devidian/OmegaXUI.git OmegaXUI
cp OmegaXUI/.git Config/
cd Config
git pull
```

You can now remove the OmegaXUI directory if you like, just type (if you are still in Config dir) `rm -R ../OmegaXUI/`. 
In case of an update you just need to `git pull` in the Config dir.
In case of an TFP update you may first execute `git reset --hard` before you pull.
