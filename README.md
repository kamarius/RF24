### Prerequisites

1. Enable SPI 1

For armbian:
Edit /boot/armbianEnv.txt adding:

```
overlay_prefix=sun8i-h3
overlays=spi-spidev
param_spidev_spi_bus=1
```

Reboot and verify the /dev/spidev1.0 exists; useful [tool for SPI testing](https://github.com/rm-hull/spidev-test)

2. Install [wiringOP-Zero](https://github.com/kamarius/WiringOP-Zero) library
3. Make & install RF24


### Original documentation

**See http://tmrh20.github.io/RF24 for all documentation**
