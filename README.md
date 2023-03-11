# Ryzen 3 3200G | OpenCore | BigSur (11)
This repo contains the EFI folder to install macOS on a build with a Ryzen 3 3200G and a NVIDIA GT630. The configuration folder was created on March 11, 2023 with the Release version 0.9 of OpenCore.

![image](https://user-images.githubusercontent.com/80203026/224507385-c41a9581-08a5-4b4f-918e-f6798053a913.png)

# Build's spec
- <b>CPU</b>: AMD Ryzen 3 3200G
- <b>GPU</b>: NVIDIA GT630 (GK 208)
- <b>RAM</b>: 8 GB DDR4
- <b>Screen</b>: 21.5" (1920x1080)

# Bios settings

<b>Security</b>
- `iGPU` **Disabled**
- `Secure Boot -> Secure Boot` **Disabled**
- `Serial Port COM` **Disabled**


<b>Startup</b>
- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No (UEFI)**

# Issues
I had a mic issue with Discord which I was able to fix by following the directions in the following repo: https://github.com/Pavo-IM/amd_hackintosh_discord_fix


# What's Working?
- [x] GT630 (incuding graphics acceleration)
- [x] CPU Power Management
- [x] Intel Ethernet port
- [x] Realtek Audio (including headphones jack)
- [x] Shutdown / Reboot
- [x] Keyboard (incuding all fn Keys)
- [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime and Netflix, and others)
- [x] Sleep / Wake (lid sleep and lid wake) (works for me you can try for yourself)

# What's not working ⚠️
- [x] Not All USB ports
