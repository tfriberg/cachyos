# cachyos
Installation and configuration of CachyOS
## Installation of CachyOS
1. Install CachyOS
2. Make existing disk available and automount by updating `/etc/fstab`
   1. Find disk UUIDs by `lsblk -f` in Konsole/Terminal
   2. With _KDE Partion manager_, installed with _Octopi_, edit mount points for all disks using UUID adding /run/media/DRIVENAME
3. Install `ntfs-3g` with _CachyOS Package installer_ to make existing NTFS drives available
## Steam
1. Set default Compatibility to _proton-cachyos (native package)_
2. Disable Shader Precaching in Steam > Settings > Downloads
## Local LLM to use with VSCode or Cursor
