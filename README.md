## awesome  
  
awesome is a highly configurable, next generation framework window manager for X.  
  
requires:

```shell
apt install awesome awesome-extra xfce4-power-manager volumeicon-alsa xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome conky tint2 libnotify-bin
```  

```shell
yum install awesome xfce4-power-manager volumeicon-alsa xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome conky tint2
```  

```shell
pacman -S awesome xfce4-power-manager volumeicon xscreensaver polkit-gnome gnome-settings-daemon network-manager-applet conky tint2 polybar
```  

  shell
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/awesome/raw/master/install.sh)"
```

Manual install:

```shell
mv -fv "$HOME/.config/awesome" "$HOME/.config/awesome.bak"
git clone https://github.com/dfmgr/awesome "$HOME/.config/awesome"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/awesome" target="_blank">awesome wiki</a>  |  
  <a href="https://awesomewm.org/" target="_blank">awesome site</a>
</p>  
