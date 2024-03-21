# Big Sur on ASUS X455LJ

## Specs
- CPU: Intel Core i3-4005U 1.7GHz
- GPU:
  - Intel HD Graphics 4400
  - NVIDIA GeForce GT 920M (disabled)
- RAM: 2+8 GB DDR3L 1600Mhz
- Storage:
  - SSD: PNY CS900 250GB
  - HDD: HGST 500GB
- Audio: Conexant CX20751/CX20752 (`layout-id: 28`)
- Ethernet: Realtek RTL8111
- WiFi: Qualcomm Atheros AR956x
- Touchpad: Focaltech PS/2

## What doesnt work?
- Bluetooth

## NOTES
- A workaround to fix slow WiFi on Atheros cards is by changing some settings on your router, mainly:
  - Channel width: 20Mhz
  - Modes: 802.11/b/g
  - Channel (probably optional): 2
 
  This should massively improve the speed of your WiFi. Credit: This [video](https://www.youtube.com/watch?v=oUJbUEsG9rI)
