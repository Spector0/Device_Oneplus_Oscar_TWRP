# initial TWRP tree for OnePlus Nord CE2 Lite
aka holi
aka Oscar

Installation:
Note: Backup stock boot image and keep it in your platform tools folder

Download and extract the Zip file and rename the boot.img to twrp.img(not mandatory)
reboot the device to bootloader
Use "fastboot flash boot twrp.img" to flash twrp
Now reboot to recovery and decrypt
Copy the stock boot image to internal storage and flash stock boot to both slots
Now do to "Advanced" option in twrp and select "Flash Current TWRP"
[Optional] press back and install Magisk zip/apk if root is required
Reboot to system
