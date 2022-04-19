# My practical OS concept
This concept is feasibly possible to make with relatively minimal actual development, mostly just configuration. It's goal is to look great, be easy for new users, have the best defaults, retain power-user level customizability, and incorporate new and useful software. It is not ideal because it takes already existing software and puts the best stuff together out of the box.
## System Base
* Based on openSUSE MicroOS with KDE desktop package
* XanMod edge default kernel, XanMod stable as backup
## Modern Desktop Technologies
* Wayland, X11 available as backup
* Pipewire (WirePlumber), PulseAudio available as backup
* Flatpak used for all non-essential apps
* Flathub enabled out of the box
## Desktop Environment Configuration
* Minimal Plasma desktop installation
* Customized Orchis Qt theme
* Papirus icon theme with tweaks
* Custom Plymouth boot screen with logo
* SDDM theme based on Chili
* Clock and resource monitor widgets
* Curated custom wallpapers
## Default Apps
* MauiKit core apps
* Librewolf
* ONLYOFFICE
## Installation
* rEFInd bootloader
* default option uses proprietary drivers if their hardware is detected
* option to boot without proprietary drivers
* ISO same as final install
* Calamares fork as installer - better looks
* Encrypted by default
* Import some preferences/data/configs from other os partition?
* Secure Boot enabled
* Proprietary drivers installed by default, option to install proprietary codecs and fonts
