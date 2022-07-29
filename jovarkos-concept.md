# My JovarkOS concept
This concept is my opinion on the direction JovarkOS should take in order to achieve its goals of usability, aesthetics, performance, and stability out of the box on the desktop.

## System Base
* Based on Arch Linux
* Linux kernel: stable branch, lts branch as backup

## Modern Desktop Technologies
* Wayland by default except for Nvidia, X11 available as backup
* Pipewire (WirePlumber), PulseAudio available as backup
* Flatpak used for all possible apps, except where it removes functionality
* Flathub enabled out of the box

## Desktop Environment Configuration
* Minimal Gnome desktop installation
* adw-gtk3 GTK3 theme
* Flat Remix icon theme (tweaks?)
* Custom Plymouth boot screen with logo
* GDM
* Curated custom wallpapers (Unsplash, or I can take some)

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
* Librewolf (firefox-gnome-theme)
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
