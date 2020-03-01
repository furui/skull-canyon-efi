# Vanilla Install with Opencore for Skull Canyon NUC6i7KYK

Disable Intel Graphics (ig-platform-id 0x12345678) to install. Then remove the ig-platform-id key after first boot. Still testing. Use your own donor serial.

Built using [Rehabman's DSDTs](https://github.com/RehabMan/Intel-NUC-DSDT-Patch) and the [Opencore Vanilla Desktop Guide](https://khronokernel.github.io/Opencore-Vanilla-Desktop-Guide/).

#### What's working

- USB 3
- Bluetooth
- Intel Graphics (didn't test DRM)
- Sleep
- DP Alt Mode via USB-C

#### What isn't

- Intel WiFi (12+6 to USB+Key-M NGFF adapter on the way)
- Random panics exasperated by heavy usage
  - Not sure what's going on here but might have something to do with the DSDTs, so next step is to manually built them from [SSDTTime](https://github.com/corpnewt/SSDTTime)
  - Syncing iCloud, using USB WiFi, or encrypting the drive with FileVault seems to cause the crashes to become more frequent
  - Not a lot of useful data in the panics as they occur in the kernel
