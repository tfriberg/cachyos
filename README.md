# CachyOS [WiP]
Installation and configuration of CachyOS

## Goals
- Have LLM run locally
- Have a *Warp* like experience with local LLM (help with running terminal commands) 
- Have a *Cursor* like experience with local LLM (help with code editing)
  - *Zed* seems okay but difficult w/o trial & error to figure out which models have Tools supported. [Create list of working models?] 

## Installation of CachyOS
1. Install CachyOS
2. Make existing disk available and automount by updating `/etc/fstab`
   1. Find disk UUIDs by `lsblk -f` in Konsole/Terminal
   2. With **KDE Partion manager**, installed with **Octopi**, edit mount points for all disks using UUID adding **/run/media/DRIVENAME**
3. (optional) Install `ntfs-3g` with **CachyOS Package installer** to make existing NTFS drives available

## Local LLM to use with terminal and code editor
* LM Studio
* ZED Text Editor
* Code OSS
* AnythingLLM Desktop
* Ollama

## Utilities
* Double Commander (File manager)
* Boxes (Virtual Machine management)
* bauh (.Appimage)
* KDE Partition Manager (Disk manager)
* Grsync (GUI for rsync)
* Oh-my-posh (make terminal look nice) [O-M-P](https://ohmyposh.dev/)
* TmuxAI [tmuxai.dev](https://tmuxai.dev)

## Good-to-know-commands
* `lsblk-f` to find eg. disk UUID's
* `sudo pacman -Syu [Appname]` to install apps via pacman

## Gaming
### Steam
1. Set default Compatibility to **proton-cachyos (native package)**
2. For Anticheat enabled/multiplayer games, set Compatibiliy to **proton-cacyos-NN.N-NNNNNNNN-slr-x86-64** which is installed with **ProtonUp-QT**
3. Disable **Shader Precaching** in Steam > Settings > Downloads
4. If game gets stuck, **Browse local files** and navigate to **steamapps/compatdata** and delete the corresponding SteamID folder

* ProtonUP-Qt
* Protontricks

### Lutris
* GoG
* Epic Games
* <del>Ubisoft Connect</del>

### Bottles
* Ubisoft Connect

### Heroic Games Launcher
* TBA

### VR
* TBA
