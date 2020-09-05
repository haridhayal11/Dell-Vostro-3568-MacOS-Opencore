# Dell-Vostro-3568-MacOS-Opencore

MacOS version    : 10.15.6

## Configuration

| Components  | Mine | Compatible |
| ------------- | ------------- | ------------- |
| CPU  | Intel Core i5-7200U  | Any Intel 7th Generation  |
| RAM  | 16GB 2133Mhz (1x16GB) | Any  |
| GPU  | Intel HD Graphics 620 | HD Graphics 620 |
| SMBIOS  | MacBookPro14,1 | MacBookPro14,1 |


## Instructions

1. Download these
   - EFI folder from this repo.
   - ProperTree https://github.com/corpnewt/ProperTree
    - GenSMBIOS https://github.com/corpnewt/GenSMBIOS
2. Copy the EFI folder to the root of EFI Partition. (delete everything else before doing this)
3. Run ProperTree and open EFI/OC/config.plist
4. Follow this guide https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html to fix iServices (Use MacBookPro14,1).
5. Save and Reboot.
