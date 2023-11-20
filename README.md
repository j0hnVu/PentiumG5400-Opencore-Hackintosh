# PentiumG5400-Opencore-Hackintosh
## EFI for my PC with a Pentium Gold G5400

**_Spec:_**
- CPU:      Intel(R) Pentium(R) Gold G5400 CPU
- Main:     ASUS EX-B365M-V5
- GPU:      Radeon RX 560
- RAM:      8GB Kingmax Dual Channel
- Ethernet: RTL8111
- Audio:    Realtek ALC887
- SSD:      Vaseky V800 128GB SATA
- HDD:      WDC 512GB SATA

**_Version installed_**:
* Big Sur: [v2.0](https://github.com/j0hnVu/PentiumG5400-Opencore-Hackintosh/releases/tag/Monterey)
* Big Sur: [v3.0 preview](https://github.com/j0hnVu/PentiumG5400-Opencore-Hackintosh/releases/tag/BigSurPreview)
* Monterey:[v2.0](https://github.com/j0hnVu/PentiumG5400-Opencore-Hackintosh/releases/tag/Monterey)

**_Note:_**
* Please remap your USB using the guide [here](https://github.com/USBToolBox/tool)
* Remember to add your SMBIOS to the config.plist

**_Tool used:_**
* [Propertree](https://github.com/corpnewt/ProperTree)
* [genSMBIOS](https://github.com/corpnewt/GenSMBIOS)
* [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg/)
* [Explorer++](https://explorerplusplus.com/download)

**_Installation:_**
1.  Assign letter the EFI partition 
* Open Minitool Partition Wizard on the installer USB
* Find FAT32 partition (~100MB) on your USB drive
* Right click on the partition, select "Assign letter", and choose the letter (e.g I:)
* Click APPLY
2.  Copy the EFI folder to the installer USB
* Open Explorer++
* Open EFI partition (I: aforementioned)
* Copy and paste the EFI folder into the partition
3.  Restart and boot to the USB.
4.  Open Disk Utility 
5.  Erase the drive or partition you wish to install Mac OS on
6.  Install MAC OS

_Adding Opencore boot option(Thanks to @big-stiff):_
- If your BIOS supports adding new boot entry, you can set with the path below
> EFI/Boot/BOOTx64.efi *(Currently using)*
or
> EFI/OC/Opencore.efi
- If your BIOS doesnt, you can easily add by using BOOTICE ( Windows required )

**If you have any question, feel free to contact me:**

- Email:    hoanganh170788@gmail.com
- Discord:  serenityowo
- Reddit:   zoolsUwU
