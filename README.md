# EFI-OC-1.0.2-Z690

EFI folder for GigaByte Z690 UD4 motherboard
Works for MacOS 15.1 Sequoia with hardware config :
- i5-12400F
- RX6600 8G
- 64Go DDR4
- NVMe WD Black

TODO : 
- Fix USB mapping or change kext to USBInjectAll (currently problems with USB Bluetooth and some USB mouse wireless dongles. And every ports are recognized as USB2 only)
- Although it works, verify that the config.plist is really compliant with OC-1.0.2 upgrade

Note : 
- If you want to use this package, do not forget to generate a valid serial (from OpenCorePkg/Utilities/macserial for exemple) and adapt your config.plist
