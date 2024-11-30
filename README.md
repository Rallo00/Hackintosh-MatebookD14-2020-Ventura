# Hackintosh Matebook D14 2020 (macOS Ventura)

I could not find an updated EFI to run safely macOS Ventura on Matebook D14 2020, so I created this one, enjoy.

REMEMBER TO GENERATE NEW SMBIOS SERIAL USING TOOLS LIKE OPENCORE CONFIGURATOR OR OTHERS!!!!!
Not doing so will prevent iCloud services from working.

![Screenshot 2024-01-02 alle 12 40 26](https://github.com/Rallo00/Hackintosh-MatebookD14-2020-Ventura/assets/106067524/5d3eb91e-cf25-493b-95eb-cbf7247cb608)

## Hardware list
* Matebook D14 2020 (14")
* Huawei custom motherboard (Intel based)
* Intel Core i7-10510U (Comet Lake) [_Intel® UHD Graphics for 10th Gen Intel® Processors_]
* RAM 16GB 3200MHz
* SSD NVMe Western Digital SN730 SDBPNTY 512GB (NVMeFix kext)
* Intel 9560HUN WiFi-Bluetooth 4.0 card (Intel kexts)
* Intel Realtek Audio (AppleALC kext)

## What Works
* Graphic acceleration
* WiFi-Bluetooth (currently having problems pairing some Bluetooth devices)
* iMessage
* Integrated touchpad and gestures
* Function buttons (brightness, media, volume)
* All iCloud functionalities
* Jack in/out external audio
* USB-C Thunderbolt (and adapters macOS comaptible)
* External HDMI
* HDMI through USB-C
* Ethernet through USB-C
* USB 2.0 and 3.0 through USB-C

## What doesn't work
* AirDrop functionality (not supported on this laptop)
  _It is not possible to swap the provided Intel Card with a macOS compatible Broadcom card like BCM94360NG because the original WiFi card uses a Intel proprietary bus CNVio, therefore the adapter on the motherboard is not compatible with BCM94360NG or equivalent that uses standard M2 2230 connectors. Even replacing the card the motherboard will not load it.
* Touchscreen (it breaks while using, no further problems are generated)
* Dedicated video card nVidia (not supported on macOS)
* Integrated WebCam (not supported on macOS)
* Integrated fingerprint reader (not supported on macOS)
* Handoff
* Facetime video (with integrated camera, works with USB external camera)
