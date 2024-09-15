## OpenCore Dell Latitude 5401 MacOS Ventura EFI

# Machine factory specs:
|**CPU**|Intel Core i5-9400H (Coffee Lake/Coffee Lake-H/Cannon Lake) 4C 8T|
|**IGPU**|Intel UHD 630|
|**SSD**|Micron NVMe 256GB|
|**Etherent/RJ45**|Intel I219-LM|
|**WLAN+BT+WWAN**|Intel Wireless AC 9560 + Bluetooth 5.0 + Intel XMM 7360 Global LTE-Advance|
|**Audio**|Realtek ALC3204|

# Machine specs post MacOS install:
|**OS**|MacOS 13.6.9 Ventura|
|**SMBIOS**|MacBook Pro 15,4 (2019)|
|**SSD**|Change this to any other SSD/NVMe as Micron NVMe are not compatible with Hackintosh|

# Functionality:
|**Built-in Display iGPU Acceleration**|Yes|
|**Touchscreen**|Yes|
|**Audio Speakers + Mic**|Yes|
|**USB-A + USB-C**|Yes|
|**USB-C Thunderbolt**|Unsure|
|**Wifi+Bluetooth**|Yes|
|**Cellular WWAN**|Unsure|
|**Trackpad**|Yes|
|**Camera**|Yes|

# Install quirks and difficulties:
**Disclaimer**: This was very difficult for me to achieve. I couldn't identify the issues when creating the EFI, and I had limited time to get this up and running, so I didn't spend too long trying to clean up the EFI folders any more than I could. This set up is working for me healthily and haven't had an issue using it for over a week now.

**2 EFI folders are present in this repo.**
- Folder = **1. EFI (for installing):** 
    - For installing MacOS Ventura 13.6.9.
    - This folder also works for daily usage, but the EFI is heavy and includes many default items that are not required.
    - Some things are not working, such as camera, bluetooth and USB-A ports.

- Folder = **2. EFI (refined):**
    - Does not allow booting to MacOS installer.
    - Allows booting into MacOS post install.

# Images:
![MacOS system info](/OpenCore-Latitude-5401/images/MacOS-SystemInfo.png)
![Cinebench R32 CPU Score](/OpenCore-Latitude-5401/images/CineBenchR32-CpuSpecs.png)

# Credit and Recognition:
- OpenCore (Dortania) - Hackintosh.
- YouTube - for various guides.
- GitHub - hosting.

Thank you all!
