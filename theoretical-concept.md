## My theoretical OS concept
This is a concept operating system using both pre-existing and hypothetical tools.

### Release Pipeline
1. Stable release source
2. Build servers
3. [openQA](https://open.qa)
4. mirrors

### Release model
* follows upstream stable channel release cycle (e.x. linux stable branch)
* custom desktop environment setup with biannual updates

### Package management
* [Guix](https://guix.gnu.org) functional package manager
* Atomic, transactional updates
* Reproducible, universal packaging
* Declarative system and package configurations in Guile Scheme
* Guix generations with regular garbage collection

### Boot Process















## System Base
* Stable linux kernel
* rEFInd boot manager (quick boot by default)
* Atomic u
* package layering with rpm-ostree
* btrfs - zstd, trim (ssds), noatime
* two ostree/btrfs snapshots: latest and backup
* Proprietary firmware and drivers included on ISO:
  - installed based on detected hardware
  - free ISO option

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
* OS-installer fork (native toolkit)
* Encrypted by default
* Import some preferences/data/configs from other os partition?
* Secure Boot enabled
* Proprietary drivers installed by default, option to install proprietary codecs and fonts
