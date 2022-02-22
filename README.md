# simg2new-dat-br
This is a script for automatic installable zip building.(this variant is for dipper, but you can modify for your own device/purpose)

## Prerequisites:
    patch
    simg2img
    img2simg(these two can go with this name, or in android-tools package! see for your distro!)
    brotli
    img2sdat(will be downloaded automatically if not found)
    
Clone repo, place system.img and boot.img near script and run script as sudo, it will do everything on its own.

This script also includes notch patching, so if you have it, and want to apply patches, make sure that modifications are compatible with your phone!
You can also comment out the part with patching. If you want you can create pull request with your own patches!
