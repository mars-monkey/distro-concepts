# My theoretical OS concept
This concept is a mix of great, already-existing tools and conceptual tools that do better than current tools.
## Release Model
### Stable
* January/February release
* Supported for 2.5 years
* Updates:
  - stable kernel
  - graphics stack
  - drivers
  - normal package versions
  - bug fixes
  - security patches
* Static:
  - **major** package versions
## System Base
* XanMod kernel
* rEFInd boot manager
* Atomic updates with libostree
* package layering with pacman
* btrfs - zstd, trim (ssds), noatime
* root partition mounted as read-only on boot
* two snapshots: latest and backup
* Proprietary firmware and drivers included on ISO:
  - installed based on detected hardware
  - free ISO option
* 
## Modern Desktop Technologies
* Wayland, X11 available as backup
* Pipewire (WirePlumber), PulseAudio available as backup
* Flatpak used for all non-essential apps
* Flathub enabled out of the box
## Desktop Environment
* Rust/C-based desktop shell and WM (COSMIC?)
* GTK4 and libadwaita fork toolkit:
  - supports theming
  - developers can choose to force their stylesheets
* GNOME-based design language
* Limited user customization in default settings app:
  - gnome-control-center contents
  - wallpaper fit
  - dark/light mode autoswitcher
  - layout changing
  - accent colours
  Configurator available for install:
  - powerful
  - granular configuration
## Default Apps
* Some forked Gnome apps
* Librewolf
* Libreoffice
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
