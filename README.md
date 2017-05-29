# DebianDog - Sid Test ISO 2016-11-19

Based on the Debian 'unstable' branch.

ISO Download:   
[DebianDog-Sid-openbox_xfce-jwm-2016-11-19.iso](https://github.com/DebianDog/Sid/releases/download/v1.0/DebianDog-Sid-openbox_xfce-jwm-2016-11-19.iso)    
[DebianDog-Sid-openbox_xfce-jwm-2016-11-19.md5](https://github.com/DebianDog/Sid/releases/download/v1.0/DebianDog-Sid-openbox_xfce-jwm-2016-11-19.md5)

Forum post at murga-linux.com (Stretch and Sid):   
[DebianDog - Stretch Preview](http://murga-linux.com/puppy/viewtopic.php?p=931862#931862)

Repository line in /etc/apt/sources.list is set to snapshot.debian (static)   
Set it to today's date to be able to get updates, e.g:
```
deb http://snapshot.debian.org/archive/debian/20161119/ unstable main contrib non-free
```    
Or change if you wish to get always updates to:
```
deb http://ftp.de.debian.org/debian/ sid main contrib non-free
```   
(then comment out the snapshot.debian line)   
And run after any change in /etc/apt/sources.list:
```
apt-get update
```    

