# OrangeFox Recovery Project for the Samsung Galaxy J7 2017

### How to build ###

```bash
# Create dirs
$ mkdir ofox ; cd ofox

# clone sync repo
$ git clone https://gitlab.com/OrangeFox/sync.git
# Clone j7y17lte repo
$ git clone https://gitlab.com/OrangeFox/device/j7y17lte.git -b fox_9.0 device/samsung/j7y17lte

# Sync
$ cd sync/ && ./orangefox_sync.sh --branch 11.0 --path ~/fox_11.0

# Build
$ source build/envsetup.sh ; lunch twrp_j7y17lte-eng ; mka recoveryimage
```
## Credits
2020 @Astrako
2022 @batuhantrkgl

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
