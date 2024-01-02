I could not find an updated EFI to run safely macOS Ventura on Matebook D14 2020, so I created this one, enjoy.

# Hackintosh Matebook D14 2020 (macOS Ventura)

REMEMBER TO GENERATE NEW SMBIOS SERIAL USING TOOLS LIKE OPENCORE CONFIGURATOR OR OTHERS!!!!!
Not doing so will prevent iCloud services from working.

![Screenshot 2024-01-02 alle 12 40 26](https://github.com/Rallo00/Hackintosh-MatebookD14-2020-Ventura/assets/106067524/5d3eb91e-cf25-493b-95eb-cbf7247cb608)

## Hardware list
Matebook D14 2020 (14")
Huawei custom motherboard (Intel based)
Intel Core i7-10510U (Comet Lake)
_Intel® UHD Graphics for 10th Gen Intel® Processors_
RAM 16GB 3200MHz
SSD NVMe Western Digital SN730 SDBPNTY 512GB (NVMeFix kext)
Intel 9430HUN WiFi-Bluetooth 4.0 card (Intel kexts)
Intel Realtek Audio (AppleALC kext)

## What Works
* Graphic acceleration
* WiFi-Bluetooth (currently having problems pairing some Bluetooth devices)
* iMessage
* Integrated touchpad and gestures
* Function buttons (brightness, media, volume)
* All iCloud functionalities

## What doesn't work
* AirDrop functionality (not supported on Intel WiFi)
* Touchscreen (it breaks while using, no further problems are generated)
* Dedicated video card nVidia (not supported on macOS)
* Integrated WebCam (not supported on macOS)
* Handoff
* Facetime video (with integrated camera, works with USB external camera)
