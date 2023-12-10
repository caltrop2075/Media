# Media
FAT drive media maintenance

used for maintaining flash media
drive list stored in flash.dat, can be used elsewhere

copies files from external media

Linux Mint:
   /home/user     system variable $HOME
   /media/user    where udisksctl mounts external drives
                  .profile/.bashrc export MEDIA="/media/$USER"
other distros ?

maintains a watched directory on flash drives
-p video is converted to text for space saving
-d text is deleted

flash drive recognized directories
all have a optional Watched sub-directory
   Movies
   Series
   mini-Series
   Videos

other projects required:
title boxes
   title-80.sh
