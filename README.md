
## My MSI Z390-A Pro 9900K Hackintosh build

I used macOS Monterey 12.01 with Opencore 0.7.4 to install macOS. The initial EFI folder was created using OC Gen-X. This was quicker than using the Dortania guide. I added the relevant SSDT files for my Coffee Lake system from the Dortania website and added it to config.plist using Propertree. By default, the front USB ports only support USB 3.0. I used Hackintool for port mapping and to generate a USBPorts.kext that I also added to config.plist using Propertree. 

### Opencore:
https://github.com/acidanthera/OpenCorePkg

### Propertree:
https://github.com/corpnewt/ProperTree

### Hackintool:
https://github.com/headkaze/Hackintool

### OC Gen-X
https://github.com/Pavo-IM/OC-Gen-X/releases

### HARDWARE

CPU: intel i9 9900K

Motherboard: MSI Z390-A Pro BIOS 7B98v1D 2021-02-08

RAM: 16GB Kingston 3200

GPU: AMD RX 5700 XT

Monitor 1: Dell 27" 1440p (Display Port)

Monitor 2: Dell 27" 1080p (HDMI)

Microphone: Samson Meteor

Headset: Corsair Void Wireless

Cooler: Corsair 115i

### Status

Everything currently works. Airdrop, Ask Siri, Continuity, the Mac App Store all work perefctly.

### Ports
![Z390-A Pro Port Layout](https://user-images.githubusercontent.com/22031708/140337881-d46ef9c4-294e-40e9-943f-65025ec8415d.png)

![Hackintool USB ports after mapping](https://user-images.githubusercontent.com/22031708/140337930-28ecd0e4-2c72-420a-8793-5ac165c92ba0.png)




