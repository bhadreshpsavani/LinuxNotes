# LinuxNotes

* Edit File: [nano Editor](https://www.nano-editor.org/)
* Create File: [touch](http://www.linfo.org/touch.html)
* Get Data from File: [cat](http://www.linfo.org/cat.html)
* Linux [Commands](http://www.linfo.org/command_index.html)

# Ubuntu

## Update & Upgrade:
```
sudo apt update
sudo apt upgrade
```

## Install Favorite Apps:
`sudo apt install vlc gimp gparted synaptic`

## Install Ubuntu Restricted Extras (Media Codecs):
`sudo apt install ubuntu-restricted-extras`

## Install Timeshift Backup Tool:
`sudo apt install timeshift`

## Install Preload:
`sudo apt install preload`

## Improve Laptop Battery:
`sudo apt install tlp tlp-rdw`

Just run the above command and you don’t need to do anything else. It’ll make your laptop battery last longer by implementing some power-saving protocols. Sorry, I forgot this one in the video. 

## Firefox Tweaks:
```
about:config
layers.acceleration.force-enabled
gfx.webrender.all
```
## Change DNS:
`8.8.8.8,8.8.4.4`

## Install Tweak Tool:
`sudo apt install gnome-tweak-tool`

## GNOME Extensions:
`https://extensions.gnome.org/​`

## Numix Theme and Icons:
```
sudo add-apt-repository ppa:numix/ppa
sudo apt-get update
sudo apt-get install numix-gtk-theme numix-icon-theme-circle
```

## Synaptic Package Manager:
`sudo apt install synaptic`

## Bleachbit:
`sudo apt install bleachbit`

## Fix Network Error:
[network-change](https://itsfoss.com/network-change-detected/)

# Fedora:

## Commands and Links:

## Update & Upgrade (DO FIRST):
`sudo dnf upgrade --refresh`

## Enable RPM Fusion:
```
sudo dnf install https://mirrors.rpmfusion.org/free/fe... -E %fedora).noarch.rpm 
https://mirrors.rpmfusion.org/nonfree... -E %fedora).noarch.rpm
```

## Install NVIDIA Drivers:
https://rpmfusion.org/Howto/NVIDIA

## Install Favorite Apps:
`sudo dnf install vlc gimp gparted kdenlive`

## Install GNOME Tweak Tool:
`sudo dnf install gnome-tweak-tool`

## Install Timeshift backup:
`sudo dnf install timeshift`

## Install Preload:
`sudo dnf copr enable elxreno/preload -y && sudo dnf install preload -y`

## Firefox Tweaks:
about:config
layers.acceleration.force-enabled
gfx.webrender.all

## Change DNS:
`8.8.8.8,8.8.4.4`

## Speed up DNF:
`echo 'fastestmirror=1' | sudo tee -a /etc/dnf/dnf.conf`
`echo 'max_parallel_downloads=10' | sudo tee -a /etc/dnf/dnf.conf`

## Install DNFDragora:
`sudo dnf isntall dnfdragora`

## Install GNOME Extensions:
`dnf install chrome-gnome-shell gnome-extensions-app`

## Install KDEConnect:
`sudo dnf install kdeconnectd`

## Install Steam:
`sudo dnf install steam`

## Better Fonts:
```
sudo dnf copr enable dawid/better_fonts -y
sudo dnf install fontconfig-font-replacements -y
sudo dnf install fontconfig-enhanced-defaults -y
```

## Install Bleachbit:
`sudo dnf install bleachbit`

