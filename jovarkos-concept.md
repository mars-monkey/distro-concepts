# My JovarkOS concept
This concept is feasibly possible to make with relatively minimal actual development, mostly just configuration. It's goal is to look great, be easy for new users, have the best defaults, retain power-user level customizability, and incorporate new and useful software. It is not ideal because it takes already existing software and puts the best stuff together out of the box.
## System Base
* Based on Arch Linux
* XanMod edge default kernel, XanMod stable as backup
## Modern Desktop Technologies
* Wayland, X11 available as backup
* Pipewire (WirePlumber), PulseAudio available as backup
* Flatpak used for all non-essential apps
* Flathub enabled out of the box
## Desktop Environment Configuration
* Minimal Gnome desktop installation
* adw-gtk3 GTK3 theme
* Papirus icon theme with tweaks
* Custom Plymouth boot screen with logo
* GDM
* Curated custom wallpapers
## Default Apps
* Core Gnome apps:
* Software
* Settings
* Console
* Files
* Text Editor
* System Monitor
* Tour
* Calculator
* Calendar
* Characters
* Cheese
* Clocks
* Contacts
* Baobab
* Evince
* Help
* Image Viewer
* Photos
* Videos
* Drawing
* Pika Backup
* Extension Manager
* Librewolf (libadwaita theme)
* ONLYOFFICE
## Installation
* rEFInd bootloader
* default option uses proprietary drivers if their hardware is detected
* option to boot without proprietary drivers
* ISO same as final install
* PopOS installer fork - libadwaita
* Encrypted by default
* Import some preferences/data/configs from other os partition?
* Secure Boot enabled
* Proprietary drivers installed by default, option to install proprietary codecs and fonts
