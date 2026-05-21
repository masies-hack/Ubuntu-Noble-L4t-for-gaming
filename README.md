# Switch Linux Gaming

Linux gaming image for Nintendo Switch based on Ubuntu Noble 24.04 KDE from Switchroot.

## Disclaimer

This project does not include:
- BIOS files
- ROMs
- Nintendo proprietary files
- Atmosphere packs
- Preconfigured Nintendo Switch system content

Users must provide their own legally obtained content.

This project is not affiliated with Nintendo.

---

## Features

- Preconfigured gaming environment
- Updated BPS 32.7 Vulkan 1.2 drivers
- Steam ARM
- Emulators preinstalled
- EmulationStation
- Performance tweaks
- Linux desktop ready to use

---

## Included Software

See:
`CREDITS.md`

---

## Proton or WINE Games
BPS 32.7 drivers with Vulkan 1.2 compatibility are already installed.
These drivers offer greater compatibility and performance for PC games.
32-bit PC games using Wine or standard Proton may experience graphical glitches with this driver version.

To avoid these graphical glitches in 32-bit PC games:
- On Steam, use any version of Proton 10. This can be the official Valve version or an alternative like GE or CachyOS.

- For games outside of Steam using Lutris or Heroic Games Launcher, it is recommended to use Wine 9.22 adapted for 32-bit games.
You can use the preconfigured prefix included in the image, "LutrisPrefix," which includes vcrun2005-al 22, DX9, 10, and 11, Nvidia Physics, and more.

For 64-bit games, you can use either Wine or Proton.

---

## Images

### FullSD
Dedicated Linux-only SD image.

### MultySystem
Prepared for multiboot setups with Android or Atmosphere.

User = switch
User & Root Password = 1234

## Downloads

Latest Release:
https://github.com/masies-hack/Ubuntu-Noble-L4t-for-gaming/releases

Archive.org Mirrors:

- FullSD
- MultySystem

---

## Installation

Flash the image FullSD using:
- BalenaEtcher
- Rufus

Boot from Hekate.

Flash the image MultySystem using:
Hekate

can use this YouTube guide
https://www.youtube.com/watch?v=
---

## Update the system correctly.

You will see a warning from Pi-Apps.
Ignore it initially.

Open the terminal. `sudo apt update && sudo apt upgrade -y`
Once updated, open Pi-Apps and update it if necessary.

Optional. Open L4t Megascript and perform an auto-update
(This may take two or three hours, as it will compile emulators like Dolphin and Azahar, among others).

---

## Discord

https://discord.gg/Mqegm7PvV9

---

## Acknowledgement
https://switchroot.org
https://github.com/cobalt2727/L4T-Megascript

Linux 4 Switch https://discord.gg/53mtKYt
L4t Megascript https://discord.gg/abgW2AG87Z

