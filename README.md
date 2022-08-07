# Hackintosh-Asus-P8Z68V-i5-2500k-RX5700-XT-Monterey
Hackintosh EFI for Asus P8Z68V i5 2500k RX5700XT Monterey 12.5 with OC 0.8.2
Due to the fact that this MB is totally obsolete you have to init boot file on you installation/efi drive to run in legacy
To do that you have to use the OpenCore/Utilities/LegacyBoot/BootInstall_X64.tool which can gain from Dortania OpenCore releases:
1. Open terminal
2. Run the BootInstall_X64.tool with sudo via drag and drop
3. Select the disk you want to make a bootable

Then you have to generate SMBIOS

I'm using wireless PCI card with MacOS native support, so take into account that LN board is not working and you have to fix it by yourself in post install.
