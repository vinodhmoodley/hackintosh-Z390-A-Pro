# hackintosh-Z390-A-Pro
My MSI Z390-A Pro 9900K Hackintosh build

I used macOS Monterey 12.01 with Opencore 0.7.4 to install macOS. The initial EFI folder was created using OC Gen-X. This was quicker than using the Dortania guide. I added the relevant SSDT files for my Coffee Lake system from the Dortania website and added it to config.plist using Propertree. By default, the front USB ports only support USB 3.0. I used Hackintool for port mapping and to generate a USBPorts.kext that I also added to config.plist using Propertree. 

HARDWARE

CPU: intel i9 9900K

Motherboard: MSI Z390-A Pro BIOS 7B98v1D 2021-02-08

RAM: 16GB Kingston 3200

GPU: AMD RX 5700 XT

Monitor 1: Dell 27" 1440p (Display Port)

Monitor 2: Dell 27" 1080p (HDMI)

Microphone: Samson Meteor

Headset: Corsair Void Wireless

Cooler: Corsair 115i

Everything currently works. Airdrop, Ask Siri, Continuity, the Mac App Store all work perefctly.

