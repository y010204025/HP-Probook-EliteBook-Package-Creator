# HP-Probook-EliteBook-Package-Creator

### SOURCE RELEASE NOT AVAILLABLE FOR NOW, WORK IN PROGRESS.

### Is a project to make easier installation of macOS on HP ProBook, EliteBook Laptop
- Fully Support macOS Sierra 10.12 and macOS High Sierra 10.13

## Credit:

- Credit: Tester: Screenz
- Credit: Tester old Project for HP ProBook Laptop: Screenz,  platinumsteel,  josh08, Zsolt Szekely, lindros4-32, YvanO21

- Credit: RehabMan for all DSDT patch
- kexts inside Clover Credit: rehabman, vit9696, Mieze, lvs1974 
- SSDT Generator Credit: Pike R Alpha
- Credit: Intel for IASL
- Credit: rehabman for patchmatic
- Credit: Apple for PackageMaker
- Credit: Clover team for Clover UEFI
- Credit: Packager chris1111

This program only uses clover and kexts injection, 
there is no kext to modify in the system and no kext 
will install in macOS system.


### How its work:
- The source is included in an image.dmg
- The package is created by PackageMaker and its .pmdoc file included in the source
- There is also a Create-Install-Media source folder to create the macOS installation tool
- The Package (Option A) can not be created on a mac using the APFS file system, PackageMaker only works on HFS+J. But as long as HP-ProBook-EliteBook-macOS.pkg was created, you can use it on APFS as on HSF+J

### What can HP-ProBook-EliteBook-macOS.pkg do:
### 6-series laptop: 
- HP Probook 4x30s, 6x60b, 
- Elitebook 2x60p, 6x60P-AMD, 8x60p

### 7-series laptop: 
- HP Probook 4x40s, 4x0 G0, 6x70b, 
- 6x70B-AMD, 6x70B-NVIDIA,  Elitebook 8x70p, 2x70p, 9x70m

### DSDT PATCH:
- Integrality of the complete system
- Intel HD 3000 Patch, Intel HD 4000 Patch (Low screen, High Screen)
- HDMI Patch, (Low screen, High Screen)
- Fan Patch
- Many more feature: Read all option in the Package HP-ProBook-EliteBook-macOS.pkg!

## Screen Shot: 
[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/captu562.png)

[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/015.png)

[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/163.png)

[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/235.png)

## Screen Shot: Source
[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/source10.png)

## Screen Shot: HP-ProBook-EliteBook-macOS.pkg 
[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/1captu42.png)

[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/2captu25.png)

[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/5captu11.png)

## Menue 6 Series
[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/menue_10.png)

## Mnue 7 Series
[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/menue_11.png)

## Note Important about HP-ProBook-EliteBook-macOS.pkg: 
- To use this program you will have to boot on a fresh installation with the Create Install Media HP Laptop tools « IMPORTANT » without any file .aml (DSDT.aml), (SSDT.aml) in  /EFI / CLOVER / ACPI / patched 

## Screen Shot: Create Install Media HP Laptop.app
[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/3captu15.png)

[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/4captu13.png)

