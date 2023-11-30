# Hackintosh-X250
Hackintosh x250, core i5-5300u, non touch

Running on Sonoma 14.1.1

HowTo:
1. First installation change your SMBIOS to Macbookpro15,2 (to pass warning installer not support for this macbookpro)
2. Disable cpu friend+cpu friend data provider from config.plist
3. Finish installation to internal hard drive
4. run OCLP
5. copy EFI folder from usb to internal hard drive, change SMBIOS to Macbookpro12,1
6. generate your cpu data provider, with one-key-cpufriend and replace in folder EFI with new generated files
7. re-renable cpu friend+cpu friend data provider again
8. generate your own iService

Tested function:
-Sleep,wake,led status
-trackpoint,trackpad,keyboard (of course i'm typing it with mybeast-x250 :v)
-minidisplay(hdmi=sound+video), minidisplay to vga (video work)
-wifi,bluetooth (speaker,mouse)

Thanks to :
1. Allah
2. Opencore
3. Opencore-Legacy-Patcher
4. Olarila
5. Airportitlwm
6. Intelbluetooth
7. Others repo (5T33z0) for providing guide on OC-Little
8. Others repo (Clay-BIOS,racka98) for providing Hackintosh on T450 series (broadwell thinkpad)

