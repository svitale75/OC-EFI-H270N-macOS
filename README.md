# An OpenCore (0.6.9) EFI that enables a Gigabyte H270N-WIFI based PC to run macOC Ventura 13.6.2

**Machine's specs:**
- Motherboard details: GIGABYTE GA-H270N-WIFI LGA1151 Intel H270 Mini ITX DDR4
- CPU details: Intel Core i3-7100 7th Gen Core Desktop Processor 3M Cache,3.90 GHz (Kaby Lake)
- GPU details: Intel HD Graphics 630

**User's to do:**
1. Download this project's latest **release** and unzip the archive
2. Download **config.plsit** from above
3. Download **OpenCore Configurator** and open config.plist or use **OpenCore configurator online** to edit config.plist
4. Under the **NVAM** section, expand 7C436110-AB2A-4BBB-A880-FE41995C9F82 and add the following to boot-args "-v keepsyms=1 debug=0x100 alcid=21"
5. Under **PlattformInfo**, select the DataHub - Generic - PLattformNVRAM. Select **iMAC18,1**
6. File > Save
7. Move the daved **config.plist** in your **EFI/OC** folder

**Credits**
- [OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [OpenCore configurator online](https://galada.gitee.io/opencoreconfiguratoronline/)
