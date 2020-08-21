## nitrogen  
  
fast and lightweight desktop background browser and setter for X Window  
  
requires:    
```
apt install nitrogen gnome-icon-theme gtkmm-2.4
```  
```
yum install nitrogen gnome-icon-theme
```  
```
pacman -S nitrogen 
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/nitrogen/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/nitrogen" "$HOME/.config/nitrogen.bak"
git clone https://github.com/dfmgr/nitrogen "$HOME/.config/nitrogen"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/nitrogen" target="_blank">nitrogen wiki</a>  |  
  <a href="https://github.com/l3ib/nitrogen" target="_blank">nitrogen site</a>
</p>  
