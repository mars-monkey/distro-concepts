# My theoretical OS concept
This concept is a mix of great, already-existing tools and conceptual tools that do better than current tools.
## Release Model
### Stable
* Latest LTS kernel
* Static LTS/ESR software
* January/February release
* Supported for 2.5 years
## Edge
* Rolling software:
*  stable kernel
* graphics stack
* desktop technologies
## System Base
* XanMod kernel
* rEFInd boot manager
* libostree updates
* package layering with pacman
* btrfs
* root partition mounted as read-only on boot
* two snapshots: latest and backup
## Modern Desktop Technologies
* Wayland, X11 available as backup
* Pipewire (WirePlumber), PulseAudio available as backup
* Flatpak used for all non-essential apps
* Flathub enabled out of the box
## Desktop Environment Configuration
* Rust/C based WM and shell
* GTK4+libadwaita fork
* HIG: GNOME
* Papirus icon theme with tweaks
* Custom Plymouth boot screen with logo
* Fork of SDDM with theme based on Chili
* Clock widget
* Curated custom wallpapers
## Default Apps
* MauiKit core apps
* Librewolf with Orchis theme
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
