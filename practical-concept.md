# My practical OS concept
This concept is feasibly possible to make with relatively minimal actual development, mostly just configuration. It's goal is to look great, be easy for new users, have the best defaults, retain power-user level customizability, and incorporate new and useful software. It is not ideal because it takes already existing software and puts the best stuff together out of the box.
## System Base
* Based on Fedora Silverblue
* XanMod stable kernel
* 2 root snapshots: latest and backup
* Btrfs with subvolumes, zstd compression, deduplication, and no access time
## Modern Desktop Technologies
* Wayland, X11 available as backup
* Pipewire (WirePlumber), PulseAudio available as backup
* Flatpak used for all non-essential apps
* Flathub enabled out of the box
## Desktop Environment Configuration
* Adwaita icon theme with tweaks
* Custom Plymouth boot screen with logo
* Curated custom wallpapers
## Default Apps
* Gnome apps
* Core Gnome apps:
* Software
* Settings
* Console
* Files
* Text Editor
* System Monitor
* Tour
* Tweaks
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
* Librewolf
* ONLYOFFICE
## Installation
* rEFInd bootloader
* default option uses proprietary drivers if their hardware is detected
* option to boot without proprietary drivers
* ISO same as final install
* OS-installer
* Encrypted by default
* Import some preferences/data/configs from other os partition?
* Secure Boot enabled
* Proprietary drivers installed by default, option to install proprietary codecs and fonts
