## nitrogen  
  
fast and lightweight desktop background browser and setter for X Window  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/nitrogen/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install nitrogen gnome-icon-theme gtkmm-2.4
```  

Fedora Based:

```shell
yum install nitrogen gnome-icon-theme
```  

Arch Based:

```shell
pacman -S nitrogen
```  

MacOS:  

```shell
brew install nitrogen
```
  
```shell
mv -fv "$HOME/.config/nitrogen" "$HOME/.config/nitrogen.bak"
git clone https://github.com/dfmgr/nitrogen "$HOME/.config/nitrogen"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/nitrogen" target="_blank" rel="noopener noreferrer">nitrogen wiki</a>  |  
  <a href="https://github.com/l3ib/nitrogen" target="_blank" rel="noopener noreferrer">nitrogen site</a>
</p>  
