# cachyos
Installation and configuration of CachyOS
## INstallation of CachyOS
1. Install CachyOS
2. Make existing disk available and automount by updating /etc/fstab
   1. Find disk UUIDs by lsblk -f in Konsole/Terminal
   2. With KDE Partion manager, installed with Octopi, edit mount points for all disks using UUID adding /run/media/DRIVENAME
3. Install ntfs-3g with CachuyOS Package installer to make existing NTFS drives available
4. 
