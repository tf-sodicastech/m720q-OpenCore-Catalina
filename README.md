# m720q-OpenCore-Catalina
Complete configuration for hackintoshing Lenovo M720Q with Opencore as bootloaded and all kext needed to make everything works.

# Computer Configuration
- CPU : Intel® Core™ i5-8400T Processor (9M Cache, up to 3.30 GHz)
- GPU : Intel® UHD Graphics 630 (Dual Display Port, HDMI)
- Memory : 2 Slots DDR4-2133
- NVMe Storage : 256 GB, PCI-E Gen3 x 4, SAMSUNG MZVLB256HAHQ-000L7 Media (Original but MacOS woulnd't install on it, using it for windows and linux)
- SATA Storage : 240 GB, PNY CS900 240GB 2.5” SATA III Internal Solid State Drive (SSD) - (SSD7CS900-240-RB) (This was added)
- Ethernet : Intel I219V7 PCI Express Gigabit Ethernet
- Wireless LAN : Fenvi M.2 NGFF WLAN BCM94360NG 802.11ac Bluetooth 4.0 WiFi Card (This was replaced)
- Audio : Realtek ALC235 (Internal Speaker, 2 audio out front ports)

# Bios Settings

![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6292.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6293.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6294.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6295.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6296.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6297.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6298.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6299.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6300.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6302.jpeg)
![Bios#1](https://github.com/tobagin/m720q-OpenCore-Catalina/blob/master/IMG_6303.jpeg)

# Whats working

- Audio: works. speaker and headphone was teste and mic was not but it should work as system it recognizes it.
- Wireless: works oob without the need of any kext.
- Ethernet: works.
- GPU: All ports works, but I only tested with main monitor plugged in through DP. but I was able to run 3 monitors.
