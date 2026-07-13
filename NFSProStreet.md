# Need For Speed: Pro Street
## EA Classics
### Info
1x DVD version
### Disc info
- DVD1:
  - D:\nfs.exe - SecuROM 7.34.0014 
### Pipeline
1. MPF (3.3.3):
   - copy protection check
2. Alcohol 120% (in Windows 7 32-bit VM)
   - SecuROM preset
   - DPM read: 2x
3. SecuROMLoader inject
   - https://github.com/nckstwrt/SecuROMLoader
   - put version.dll and injector into game folder
   - put version.json
4. Run from terminal
   - Open bash terminal from Lutris
   - Navigate to game folder
   - run `wine VersionInjector.exe`
### Working on
- Linux Mint
  - Lutris
    - run from terminal