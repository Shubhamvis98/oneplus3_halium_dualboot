# DUALBOOT ONEPLUS 3 (UBUNTU TOUCH & ANDROID)

## MAKE SURE YOU HAVE BACKUP OF YOUR ANDROID BOOT IMAGE
## IF ANYTHING GOES WRONG THEN YOU CAN JUST REFLASH THE ANDROID BOOT IMAGE TO BOOT INTO ANDROID

Download the release package and extract it.\
Now run ```bash install.sh``` to install the ubports\
To boot in ubports, flash the halium_oneplus3_dualboot.img using:
<p align="center">
  <code>dd if=halium_oneplus3_dualboot.img of=/dev/block/by-name/boot</code>
  or
  <code>bash ubuntu.sh</code>
</p>

Now restart your device...

## TO BOOT INTO ANDROID
Run ```android``` in ubuntu terminal and restart your device to boot into android

## TO UNINSTALL UBPORTS
Run ```bash uninstall.sh``` to uninstall ubports system along with its data
