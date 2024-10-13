# ThinkPad E15 i7 10510U OpenCore 1.0.1
Open Core 1.0.1 EFI for ThinkPad E15 I7 10510U

EFI Folder is for Ventura<br>
Sonoma/EFI is for Sonoma with BCM94630NG Kexts<br>  
* Must run OpenCore-Patcher https://github.com/dortania/OpenCore-Legacy-Patcher/releases
* Post-install Root Patch
* Start Root Patching



Included Drivers for Dual Boot with Windows 11 <br>  
* Drivers included for the BCM94360NG network card for Plug and Play Ventura <br>  
Install drivers in the folloing order <br>  


1. Install_PCIE_Win11_11016_11212023_02232024
   * Realtek ethernet driver to avoid conflicts with BCM94360NG
2. BCM94360NG_Driver\wifi\broadcom_wlan_7.35.317.3\setup
3. bluetooth\DPinst

DiskGenius is included to edit boot entries and order
     

