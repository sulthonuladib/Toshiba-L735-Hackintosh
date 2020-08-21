# Hackintosh Toshiba Satellite L735

i just found my old laptop and hackintosh it of course xD

## Specification

-   Processor: Intel Core Intel Core i3 2350M
-   GPU: Intel HD 3000
-   RAM: 2 GB DDR3
-   Wifi Card: Atheros AR9285, you can see fixing method here [a relative link](./AR9285_Fix.md)
-   LAN Card: Realtek RTL8111

## BIOS Configuration

Just default then Enable Legacy USB Support, and make sure Boot mode is Normal not in fast mode

## How to use

-   Create installer with createinstallmedia method with HFS+ and GUID Partition Map
-   Clone or Download this repository
-   Run BootInstall.command on helpers folder with sudo mode to your USB installer to create Legacy Boot mode
-   Mount EFI of your USB partition
-   Copy EFI folder from this repository
-   Boot to your installer USB
-   After Installation Complete also run bootinstall.command to your HDD Destination on helpers mode with sudo mode and copy EFI folder to your EFI of your HDD/SSD
