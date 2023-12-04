# An OpenCore (0.6.9) EFI that enables a Gigabyte H270N-WIFI based PC to run macOC Ventura 13.6.1

**Machine's specs:**
- Motherboard details: GIGABYTE GA-H270N-WIFI LGA1151 Intel H270 Mini ITX DDR4
- CPU details: Intel Core i3-7100 7th Gen Core Desktop Processor 3M Cache,3.90 GHz (Kaby Lake)
- GPU details: Intel HD Graphics 630

**User's to do:**
- If macOS Ventura 13.6.1 is already installed then:
1. Download this project's latest **release** and unzip the archive, this will give you a single folder named **EFI**
2. Copy the  **EFI** folder into the root of your drive **EFI partition**
3. Download **config.plsit** from the above repository
4. Download **OpenCore Configurator** or use **OpenCore Configurator On Line** to edit **config.plist**
5. Under the **NVAM** section, expand 7C436110-AB2A-4BBB-A880-FE41995C9F82 and add the following to boot-args "-v keepsyms=1 debug=0x100 alcid=21"
6. Under **PlattformInfo**, select the DataHub - Generic - PlattformNVRAM. Select **iMAC18,1**
7. Save **config.plist**
8. Move the saved **config.plist** into your **EFI/OC** folder of your **EFI** partition
  
- If macOS Ventura 13.6.1 is NOT already installed then:
1. Download **OpneCore Legacy Patcher**
2. Create mac OS istaller for macOS **Ventura 13.6.1** to a drive
3. Build and Instal OpenCore to the same drive
4. Mount the drives **EFI** partition of your instal drive and delete all of its content
5. Download this project's latest **release** and unzip the archive, this will give you a single folder named **EFI**
6. Copy the  **EFI** to the root of your instal drive **EFI partition**
7. Download **config.plsit** from the above repository
8. Download **OpenCore Configurator** or use **OpenCore Configurator On Line** to edit **config.plist**
9. Under the **NVAM** section, expand 7C436110-AB2A-4BBB-A880-FE41995C9F82 and add the following to boot-args "-v keepsyms=1 debug=0x100 alcid=21"
10. Under **PlattformInfo**, select the DataHub - Generic - PlattformNVRAM. Select **iMAC18,1**
11. Save **config.plist**
12. Move the saved **config.plist** into your **EFI/OC** folder of your instal drive **EFI** partition
    
**Credits**
- [OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [Acidanthera](https://github.com/acidanthera)
- [OpenCore Legacy Parcher](https://dortania.github.io/OpenCore-Legacy-Patcher/)
- [OpenCore Configurator On Line](https://galada.gitee.io/opencoreconfiguratoronline/)

<img src="/Docs/Imgs/001.png" width="640"/>
<img src="/Docs/Imgs/002.png" width="640"/>
<img src="/Docs/Imgs/003.png" width="640"/>
<img src="/Docs/Imgs/004.png" width="640"/>
