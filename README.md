# Ryzentosh-MSI-X470-RX550LEXA-BCM94360CS2

## Introduction

After a long struggle, i was able to run the AMD Radeon RX 550 Lexa graphics card in hackintosh without any problems. Other than that i believe there are different things in my EFI that can help people. Feel happy while using it :)

## Software Compatibility

- Ventura (13.x)
- Monterey (12.x)
- Big Sur (11.x)
- Catalina (10.15.x)

## Important

RX 550 Lexa only works in **(_SB_).(PCI0).(GPP8)** location path on hackintosh. If you have this location path, you are very lucky. Because it will work smoothly.

**Follow these steps to find your location path**
1. Open Windows and go to device manager.
2. Find your graphics card and right click on it and click properties.
3. Click details in the opened tab, then find the device path from the property tab.
4. You will see two values. One will be like this **ACPI(_SB_)#ACPI(PCI0)#ACPI(GPP8)#PCI(0000)**
5. If your location path is as i mentioned, you are lucky. If not, sorry the graphics card will not work.

## My System Specs

| **Component**    | **Model**                                  |
| ---------------- | ------------------------------------------ |
| CPU              | AMD Ryzen 5 3600                           |
| Motherboard      | MSI X470 Gaming Plus Max                   |
| RAM              | Crucial Ballistix Sport LT Red 8GB x 2     |
| GPU              | AMD Radeon RX 550 4GB 512SP                |
| Audio Chipset    | Realtek ALC897                             |
| Ethernet         | Realtek RTL8111H                           |
| WiFi & Bluetooth | Fenvi FV-HB1200 (BCM94360CD2)              |
| OS Disk (NVMe)   | Crucial P5 500GB                           |

## Working Status

- Ethernet
- WiFİ
- Bluetooth
- Airdrop
- Handoff
- Front and rear sound outputs
- Front and rear USB 2.0 & 3.X outputs
- AMD Ryzen Power Gadget (Fan control, power control etc.)
- Deep sleep
- iMessage and FaceTime
- H.264, HEVC hardware decoding, encoding, video processing


