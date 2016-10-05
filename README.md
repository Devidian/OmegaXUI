# OmegaXUI
7 Days To Die XUI by Devidian

Some additions to the basic UI, adding food, water, xp bars and Temperature / Elevation level.
Also adds a compass center indicator.

## Screenshot
![alt text](http://xui.omega-zirkel.de/screen002.jpg "XUI Screenshot #2")

## Installation & Update Information
The current master is ONLY for Alpha 15, dont try to use with a lower Alpha version.
### Linux Dedicated Server

Connect to your server via ssh and go to your Data folder. This for example is when you use allocs fixes:

```
cd /home/sdtd/engine/Data/
```

Now clone the repository, switch to the repository and pull for current master

```
git clone https://github.com/Devidian/OmegaXUI.git OmegaXUI
cd OmegaXUI
git pull
```

Last step is to copy all files to your Config dir with (-R to override existing files)

```
cp -R ./* ../Config/
```

To update, just pull the repository again and copy all files over to the Config directory.

### Windows DS or Client (All OS)
just download the files from github and copy them to your Config folder


## Other credits
###StompyNZ for RWG Preview Enhancements
![alt text](http://xui.omega-zirkel.de/rwgpreviewer.jpg "RWG Preview Enhancements")