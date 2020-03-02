# Vanilla Catalina Install with Opencore for Skull Canyon NUC6i7KYK

Still testing. Use your own donor serial.

Built using the [Opencore Vanilla Desktop Guide](https://khronokernel.github.io/Opencore-Vanilla-Desktop-Guide/).

#### What's working

- USB 3
- Bluetooth
- Intel Graphics (didn't test DRM)
- Sleep
- DP Alt Mode via USB-C

#### What isn't

- Intel WiFi (Using Asus Nano 802.11AC dongle with [chris1111's driver](https://github.com/chris1111/Wireless-USB-Adapter-Clover) and 12+6 to USB+Key-M NGFF adapter on the way)
- Hot plug DP
  - Unplugging and replugging in the USB-C won't show any display
