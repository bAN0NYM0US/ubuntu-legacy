# Ubuntu Legacy 23.04 - Mainline 6.1.12 / T2 / 6.2.0

![alt text](https://i.imgur.com/qXsELnT.png)

# Info
  This is Ubuntu 23.04 running the mainline stable or release candidate kernel.
  SNAP has been completely removed, providing only legacy support with APT.
  Added T2 Kernel, Wifi and Touchbar drivers for 2016-2020 Macs (T2 build only).

# Downloads
[Updated February 14th 2023]

## [Ubuntu Legacy 23.04 / Mainline 6.1.12](https://drive.google.com/file/d/1wi6HGx8lNDk91ZmnuD3v3iJe3k9OuT1-)

## [Ubuntu Legacy 23.04 / Mainline 6.1.12 T2](https://drive.google.com/file/d/1UJ4rb385P9dAEvFdIYshkIyHHH97pe1Y)

## [Ubuntu Legacy 23.04 / Mainline 6.2.0-rc8](https://drive.google.com/file/d/18h5nL4yKGeph1qtdTguEpM2QXimIQjCQ)

# Updating Mainline and RC:
  - Visit the [Mainline Ubuntu Kernel](https://kernel.ubuntu.com/~kernel-ppa/mainline/?C=N;O=D) page to download the latest you would like to use.
  - cd ~/Downloads (or which ever folder you saved all the .deb files to)
  - sudo dpkg -i *.deb (this will install EVERY .deb file in the directory)

# Updating Mainline T2 (2016 to 2020 Intel Macs)
  - Download the latest [Lunar Lobster T2 Kernel 6.2.0](https://drive.google.com/file/d/13L2l9H-CkakAqqnMTmxIwQWgPLn2RRUy) I've compiled.
  - Same install process at the other kernels.

# Revert to older Kernel:
  - Hold "Space" while booting to show Systemd and select older kernel as a boot option.
  - Use Shift + or Shift - to increase or decrease Systemd boot menu exposure.
  
# Changelog

### Added
  - neofetch
  - gnome tweaks
  - gnome shell extensions
  - universe ppa
  - multiverse ppa
  - mozilla ppa
  - APT firefox

### Changed
  - linux kernel 6.1.12
  - linux-kernel 6.1.12-t2
  - linux kernel 6.2.0-rc8
  - Grub menu now says "Ubuntu Legacy"
  - Neofetch now reads "Ubuntu Legacy 23.04"
  - Grub menu timer from USB set to 69 seconds (..nice)

### Removed
  - snap packages
  - snapd
  - snap-store
  - old kernels

# Contributions
  - [Ubuntu 23.04](https://cdimage.ubuntu.com/daily-live)
  - [Mainline Kernel](https://kernel.ubuntu.com/~kernel-ppa/mainline/?C=N;O=D)
  - [T2 Linux Kernel](https://github.com/t2linux/T2-Ubuntu-Kernel)
  - [Cubic](https://github.com/PJ-Singh-001/Cubic)
