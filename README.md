# myHackintosh

Here I'll explain the steps I'm following in order to install El Capitan 10.11 in my Laptop.
Specifications:
- HP DV6-3180ES
- CPU: Intel i5 460M
- Graphics:
- ATI Mobility Raedon 5650
- Indel HD 1st gen (Device ID 0046 and Vendor ID as 8086)
- Wifi:
- Ethernet:
- Sound:

### Fix USB error
Using Clover Configurator, use kext patch feature, I applied the following patch:
Name: AppleUSBXHCIPCI
Find: <83bd8cfeffff10>
Replace: <83bd8cfeffff15>
Comment: Change 15 port limit to 20 in AppleUSBXHCIPCI

Copy USBInjectAll.kext in /EFI/CLOVER/kexts/10.11/

### Fix Graphics issues
Remove AppleIntelHDGraphicsFB.kext from System/Library/Extensions ??????
Patch Intel card in Clover and set fake id 0x01660003

### Boot flags
cpus=1
GraphicsEnabler=No

### Wifi

### Ethernet

### Sound

### Keyboard & multi-touch touchpad

### Webcam

### Memory Card Reader


### Version
0.1
