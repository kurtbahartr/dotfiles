Version 1.1.2
https://github.com/dianaw353/dotfiles/releases/tag/V1.1.2
--------------------------------------------------------
**Changes**
- Switch to wezterm terminal instead of kitty
- Add Noto fonts
- Relocate where NetworkManager is enabled and started
- Restart NetworkManager and Bluetooth services
- Add a ZSH alias to remove `pacman`'s `db.lck`
- Enable experimental D-Bus interfaces for Bluetooth
- Add new AUR package: `bluetooth-autoconnect`

Version 1.1.1
https://github.com/dianaw353/dotfiles/releases/tag/V1.1.1
--------------------------------------------------------
**Script**
- Simplify dependencies installation on ags/hyprland

**Fixes**
- Autostart hyprland plugins and polkit 
- Switch hibronate to suspend for better system compatibility
- Keybind fixes
- Settings page header fix

Version 1.1
https://github.com/dianaw353/dotfiles/releases/tag/V1.1
--------------------------------------------------------
**Script**
- Hyprland & ags refactoring
- Speed up moveing files to correct location
- Change laptop workarounds
- Rename gpu_drivers to drivers
- Add installation for cpu ucode
- Make sure NetworkManager is enabled
- Gaming role now has compatibillity layer dependencies, utilities, and launchers
- Add android-tools to user_packages
- Update Prism Launcher dependency
- Replace Firefox with Zed Browser
- Replace Alacritty with Kitty
- Replace Blueman with Bluetuith 
- Copy 'usr/share/pipewire' folder to '/etc/pipewire' to fix screenshare
- Pipewire loads by default
- Change core/custom packages so they are not dependent on arch only features

**Ags**
- Added config

**Fastfetch**
- Cleaner look

**Hyprland**
- Updated some keybindings
- Add hypr-dynamic-cursor plugin for shake to find cursor
- Autostart polkit-gnome

**Hypridle**
- Screen no longer locks when in fullscreen
- Pause all players when screen locks

**Hyprlock**
- Get correct pfp and wallpaper

Version 1.0.7
https://github.com/dianaw353/dotfiles/releases/tag/V1.0.7
--------------------------------------------------------
**Script**
- More Refactoring

**Hyprland**
- Add polkit-gnome
- New lock screen keybind

**Hypridle**
- Shorten time to dim, screen/keyboard backlight, lock screen

**Fixes**
- Make sure screen locks when laptop lid is closed

Version 1.0.6
https://github.com/dianaw353/dotfiles/releases/tag/V1.0.6
--------------------------------------------------------
**Script**
- Add gaming module, option to install minecraft
- Change masa drivers to only install for amd/intel
- Add 32bit drivers
- Added AMD close source drivers
- Added blocks to each roles

**Fixes**
- gpu_drivers & package_cleanup runs correctly

Version 1.0.5
https://github.com/dianaw353/dotfiles/releases/tag/V1.0.5
--------------------------------------------------------
**Script**
- Reorganise some flags
- GTK window buttons configuration (no buttons default)
- Command to disable oh-my-posh update warnings
- Add systemd-timesync module
- Move many apps to core_apps
- Add custom_apps
- Update installation method
- Remove sunroof & spotube
- Add custom_apps
- Enable systemd-timesync module
- Simplify group_vars/all.yml
- Move system to pre_tasks

**Fixes**
- Add dejavu-nerd font, github-cli
- Remove sunroof
- Remove is_nvidia flag
- dotfiles script now download dotfiles

Version 1.0.4
https://github.com/dianaw353/dotfiles/releases/tag/V1.0.4
--------------------------------------------------------
**Script Changes**
- WIP/ALPHA: Add variable for driver preference for Nvidia GPUs
- Make terms for package managers more generic
- Merge audio/bluetooth into system role

**Hyprland**
- Add hypridle & hyprlock

**Fixes**
- Install openssh as a preliminary dependency
- Install some missing packages for a barebones Arch install fresh out of the wiki replication
- Separate new Nvidia cards from old, unsupported ones
- Install Nouveau dependencies if opted out of proprietary Nvidia drivers

Version 1.0.3
https://github.com/dianaw353/dotfiles/releases/tag/V1.0.3
--------------------------------------------------------
**Fixes**
- Add playerctl
- Move avatar to pfp and mountain to wallpaper in Pictures
- Premission improvements

Version 1.0.2
https://github.com/dianaw353/dotfiles/releases/tag/V1.0.2
--------------------------------------------------------
**Script Changes**
  - Install KVM
  - Set up KVM w/ 3d acceleration support
  - Detect if user is using VM
  - Add is_vm for additional configuration
    - Change hyprland env's depending if is_vm is set to true
  - Add is_nvidia for additional configuration
    - Change hyprland env's depending if is_nvidia is set to true
  - Greetd gets images from assets

**Hyprland Changes**
- QT_QPA_PLATFORMTHEME,qt5ct added 
- Add gamemode script
- Change missioncenter windowrules to use class instead of title and preferences to be shown in the center of the screen
- Autostart hyprpaper and add hyprpaper config

**Fixes**
- Hyprland scripts are now executable
- Ansible host fixes 
- Rename gpu_drivers.yml to main.yml
- Rebase main.yml
- Add xdg-desktop-portal-gtk to system compatibility packages
- Move Greetd config to correct location 
- Install all ansible requirements
- Fix cursor install to install correct package
- Replace swww with hyprpaper
- Add assets folder
  
Version 1.0.1
https://github.com/dianaw353/dotfiles/releases/tag/V1.0.1
--------------------------------------------------------
- Script: Add sunroof and spotube as new applications
- Script: Add 4 new flags
  - Hyprland: Add autostart template for the following to work
    - Icons: Add new icons section
      - Add flag for cursor package (AUR ONLY ATM) 
      - Add flag for cursor theme
      - Add flag to change cursor size
  - Pacman: Add for chaotic_aur
    - Update pacman conf to also have ILoveCandy and VerbosePkgLists
- Script: rate-mirrors added
  - Add rate-mirrors package
  - Update pacman & chaotic aur mirrors list
- Script: Refactor framework workaround to laptop workarounds
- Update pacman conf to also have ILoveCandy and VerbosePkgLists
- Refactor aur_helper
- Add script to backup dotfiles
- Add Hyprshot
- Add keybindings for hyprshot
- Add keybindings to set active windodw to fullscreen
- Add libadwaita as a dependencie

Version 1.0
https://github.com/dianaw353/dotfiles/releases/tag/V1.0
--------------------------------------------------------
- Inital Release
