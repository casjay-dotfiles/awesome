## awesome  
  
DESCRIBE  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/awesome/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install awesome awesome-extra xfce4-power-manager volumeicon-alsa xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome conky tint2 libnotify-bin
```  

Fedora Based:

```shell
yum install awesome xfce4-power-manager volumeicon-alsa xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome conky tint2
```  

Arch Based:

```shell
pacman -S awesome xfce4-power-manager volumeicon xscreensaver polkit-gnome gnome-settings-daemon network-manager-applet conky tint2 polybar
```  

MacOS:  

```shell
brew install
```
  
```shell
mv -fv "$HOME/.config/awesome" "$HOME/.config/awesome.bak"
git clone https://github.com/dfmgr/awesome "$HOME/.config/awesome"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/awesome" target="_blank" rel="noopener noreferrer">awesome wiki</a>  |  
  <a href="https://awesomewm.org" target="_blank" rel="noopener noreferrer">awesome site</a>
</p>  
