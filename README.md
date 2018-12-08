# RamDisq
A very simple script that generates an AFPS ram disk in macOS Mojave (I have not tried with previous version of macOS).

The RamDisk will be deleted after ejection.

# Set a cache on RamDisk
You can use it with chromium :
* Open Terminal app ;
* `rm -rf ~/Library/Caches/Chromium/Default` ; It will remove the cache on your HDD.
* `ln -s /Volumes/RamDisq ~/Library/Caches/Chromium/Default` ; will link the cache with the ram disk. The cache will be destroyed on reboot.
* A macOS binary is available (RamDisq.zip) made with Platypus . You can add the binary/the script to your startup items.
