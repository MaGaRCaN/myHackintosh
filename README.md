# myHackintosh

Here I'll explain the steps I'm following in order to install El Capitan 10.11 in my Laptop.
Specifications:
- HP DV6-3180ES
- CPU: Intel i5 460M
- Graphics:
  1. ATI Mobility Raedon 5650
  2. Indel HD 1st gen (Device ID 0046 and Vendor ID as 8086)
- Wifi: Qualcomm Atheros AR9285
- Ethernet: Realtek PCIe GBE Family Controller
- Sound: IDT 92HD81B1X @ Intel Ibex Peak PCH - High Definition Audio Controller [B-2]	PCI
- Keyboard & multi-touch touchpad: 
- Standard PS/2 keyboard 
- Synaptics PS/2 Port TouchPad

### Fix CPU error
-XXX.kext

### Fix USB error
-XXX.kext

### Fix Graphics issues
- AppleIntelHDGraphicsFB has the Frame Buffer info copy old one
- Copy updated from http://www.insanelymac.com

### Boot flags

### Wifi
*working*

### Ethernet
- Need to write any MAC

### Sound
- Remove AppleHDA.kext
- Copy AppleHDA 2.kext
- Copy HDAEnabler.kext

### Keyboard & multi-touch touchpad
**Issues pressing buttons...**

### Webcam
*working*

### Memory Card Reader
*working*

### Version
0.2b
