# UltramrineMK

💙 This uses [zirconium-mkosi](https://github.com/tulilirockz/zirconium-mkosi) as a template, thank you!

# Purpose

Ultramarine bootc image made with Mkosi.

Mix and match profiles!


Tested inside a fedora:rawhide distrobox

Bootc support is not yet tested

## Profiles

### - Bootc

Required for generating bootc images

### - Base

Simple base with good hardware support

### - Gnome

Install the Gnome desktop

### - Plasma

Install the Plasma desktop

### - DX

Utilities for developers (Docker, qemu and more)

### - Kernel-latest \ Kernel-lts

Which kernel you want? (LTS for Kwizart)

### - Nvidia

Drivers for Nvidia GPU


# How to rebase

```bash
sudo bootc switch --enforce-container-sigpolicy "ghcr.io/jumpyvi/ultramarine-mk-gnome:latest"
```

# Huge thanks
- https://github.com/tulilirockz/zirconium-mkosi
- https://github.com/tuna-os/tunaOS
- https://github.com/bootcrew
- https://github.com/ublue-os/bluefin-lts
- https://github.com/Ultramarine-Linux/bootc