## My theoretical OS concept
This is a concept operating system using both pre-existing and hypothetical tools based on the Guix System GNU Linux distribution.

### Release Pipeline
1. Stable release source
2. Build servers
3. [openQA](https://open.qa)
4. Mirrors

### Release model: follows upstream stable channel release cycle

### Package management
* [Guix](https://guix.gnu.org) functional package manager
* Atomic, transactional updates
* Reproducible, universal packaging
* Declarative system and package configurations in Guile Scheme
* Guix generations with regular garbage collection
* Custom repo with free and proprietary software

### Boot Process
* rEFInd boot manager (accessed with keybind after POST)
  - Recovery: live environment with advanced recovery tools available
  - Guix generations: different snapshots of the system
* Plymouth boot logo
* herd init system
* proprietary firmware and drivers included (free ISO option)

### Modern Desktop Technologies
* Wayland, X11 available as backup
* Pipewire (WirePlumber), PulseAudio available as backup
* Flatpak installed for increased app library

### Desktop Environment
* COSMIC-based desktop
* Iced toolkit
  - supports system theming
  - developers can choose to force their stylesheets
* Adwaita-based design language
* Limited user customization in default settings app:
  - gnome-control-center contents
  - wallpaper fit
  - dark/light mode autoswitcher
  - layout changing
  - accent colours
  Configurator available for install:
  - powerful
  - granular configuration

### Default Apps
* COSMIC default
* Librewolf
* Libreoffice

### Installation
* rEFInd bootloader
* default option uses proprietary drivers if their hardware is detected
* option to boot without proprietary drivers
* ISO same as final install
* Custom Iced installer
* Encrypted by default
* Import some preferences/data/configs from other os partition?
* Secure Boot enabled
* Proprietary drivers installed by default, option to install proprietary codecs and fonts
