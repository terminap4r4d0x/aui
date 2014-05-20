#Unattended Arch Install
## Based on Archlinux Ultimate Install Script

My intial objective is an unattended install of a completely configured Arch system with Openbox as the WM. As such this will be configured to suit only my individual taste.
## Prerequisites

- A working internet connection
- Logged in as 'root'

## How to get it
### With git
- Upgrade your system and install git: `pacman -Syu & pacman -S git`
- get the script: `git clone https://github.com/terminap4r4d0x/aui.git 

## How to use
- ais mode: `cd <dir> && ./ais`
- aui mode: `cd <dir> && ./aui`

## Archlinux Install Script (ais)
- Configure keymap
- Select editor
- Automatic configure mirrorlist
- Create partition
- Format device
- Install system base
- Configure fstab
- Configure hostname
- Configure timezone
- Configure hardware clock
- Configure locale
- Configure mkinitcpio
- Install/Configure bootloader
- Configure mirrorlist
- Configure root password

## Archlinux Ultimate Install (aui)
- Backup all modified files
- Install additional repositories
- Create and configure new user
- Install and configure sudo
- Automatic enable services in systemd
- Install an AUR Helper [yaourt, packer, pacaur]
- Install base system
- Install systemd
- Install Preload
- Install Zram
- Install Xorg
- Install GPU Drivers
- Install CUPS
- Install Additional wireless/bluetooth firmwares
- Ensuring access to GIT through a firewall
- Install DE or WM [Cinnamon, Enlightenment, FluxBox, GNOME, KDE, LXDE, OpenBox, XFCE]
- Install Developement tools [Vim, Emacs, Eclipse...]
- Install Office apps [LibreOffice, GNOME-Office, Latex...]
- Install System tools [Wine, Virtualbox, Grsync, Htop]
- Install Graphics apps [Inkscape, Gimp, Blender, MComix]
- Install Internet apps [Firefox, Google-Chrome, Jdownloader...]
- Install Multimedia apps [Rhythmbox, Clementine, Codecs...]
- Install Games [HoN, World of Padman, Wesnoth...]
- Install Fonts [Liberation, MS-Fonts, Google-webfonts...]
- Install and configure Web Servers
- Many More...

