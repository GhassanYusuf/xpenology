# XPNOLOGY
This is to just explain the xpenology installation

referance link [https://xpenology.com/forum/topic/7973-tutorial-installmigrate-dsm-52-to-61x-juns-loader/](https://xpenology.com/forum/topic/7973-tutorial-installmigrate-dsm-52-to-61x-juns-loader/)

## What do we need ?
1. An old computer - The Hardware That We Need
2. Flash Memory 8GB or Above - For Installing And Running Synology
3. Hard Drives - For Storage
4. [XPNOLOGY LOADER - FILES](https://mega.nz/folder/yQpw0YTI#DQqIzUCG2RbBtQ6YieScWg/folder/iJZjAJoa)
5. [XPNOLOGY OS - Image](https://global.download.synology.com/download/DSM/release/6.1.7/15284/DSM_DS3615xs_15284.pat?model=DS3615xs&bays=12&dsm_version=6.1.7&build_number=15284)
6. [OSFmount - Application ***"To Change VID/PID To grub.cfg file"***](https://www.osforensics.com/downloads/osfmount.exe)
7. [Etcher - Application](https://www.balena.io/etcher/)


## Accident Update
Incase you accedentally upgraded and the system wen un responsive

1. Turn off machine and remove usb with v1.02a loader. Keep that usb aside in case you need it later.
2. Burn new loader v1.02b on usb. Make sure to edit the grub.cfg file like you did for v1.02a (vid/pid, SN, MAC etc). When done, plug the usb key on the machine
3. Turn on the machine
4. Use find.synology.com or Synology Assistant to find the machine on the network
5. Migrate the machine by following the steps indicated on screen. You will be asked to provide the PAT file for 6.1.x so download it first. Download links can he found here:
