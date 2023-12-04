# An OpenCore (0.6.9) EFI that enables a Gigabyte H270N-WIFI based PC to run macOC Ventura 13.6.2

**Machine's specs:**
- COU details: Intel Core i3-7100 7th Gen Core Desktop Processor 3M Cache,3.90 GHz (Kaby Lake)
- GPU details: Intel HD Graphics 630

**To do for users:**
1. Download config.plsit from above
2. Download OpenCoore Configurator and open config.plist
3. Under the NVAM section, expand 7C436110-AB2A-4BBB-A880-FE41995C9F82 and add the following to boot-args "-v keepsyms=1 debug=0x100 alcid=21"
4. Under PlattformInfo, selected the DataHub - Generic - PLattformNVRAM. Select iMAC18,1.
5. File > Save
6. Move the daved config.plist in your EFI/OC folder
