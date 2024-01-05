# ziggotv.github.io

## repository.ziggotv

### About

-Watch Ziggo Live TV

### Features

-Unofficial 3rd Party repo and plugins for Kodi

-Watch live TV for supported channels in your subscription

-Replay programs from the last 7 days for supported channels in your subscription

-Watch video on demand (VOD) content

### Maximum supported Resolution

- Ziggo: 1080P

### Required

-Subscription to provider Ziggo (not free)

-Kodi 20 or higher with Widevine Support (free)

### Installation
Instructions adopted from the kodi wiki, see [HOW-TO:Install add-ons from zip files](https://kodi.wiki/view/HOW-TO:Install_add-ons_from_zip_files)

-Step 1: Download the repository.ziggotv ZIP-file from [here](https://ziggotv.github.io/ziggotv/repository.ziggotv/repository.ziggotv-0.9.2.zip)

-Step 2: To access the Add-on browser see: [How to access the Add-on browser](https://kodi.wiki/view/Add-on_manager#How_to_access_the_Add-on_browser) or [How to access the Add-on manager](https://kodi.wiki/view/Add-on_manager#How_to_access_the_Add-on_manager)

-Step 3: Select Install from zip file

-Step 4: If you have not enabled Unknown Sources, you will be notified that it is disabled. If you wish to enable select Settings, if you do not wish to enable select OK. If you have already enabled Unknown sources skip to Step 7.

-Step 5: When you select Settings you will be taken to the Add-ons settings window. Enable Unknown sources if you wish to install your add-on or repository from a zip file.

-Step 6: After you enable Unknown sources you will be presented with a Warning. Make sure you read and understand this warning, then select Yes if you wish to proceed.

-Step 7: If you have selected Yes and enabled Unknown sources you can then navigate back to the Add-on browser and once again select Install from zip file

-Step 8: You will now be presented with a browser window where you can navigate to where your zip file is stored. Your zip file can be stored anywhere your device has access to and can be either on local storage or a network share.

-Step 9: Once you have navigated to the zip file you downloaded in Step 1, select it then select OK. You will be notified when the repository is installed succesfully.

-Step 10: Navigate back to the Add-on browser and select Install from repository

-Step 11: Navigate to Ziggotv repository

-Step 12: Navigate to Video add-ons

-Step 13: Select the ziggotv addon to install, dependencies will automatically be installed

### Additional instructions for general Linux / OSMC

- The addons require the pycryptodomex packages, which is not included in OSMC and possibly general linux distributions

- These steps are not required for CoreELEC/LibreELEC/Windows/Android

- Execute the following commands in a terminal:

```
sudo apt-get install python3-crypto
sudo apt-get install build-essential python3-pip
sudo python3 -m pip install -U setuptools
sudo python3 -m pip install wheel
sudo python3 -m pip install pycryptodomex
```

### Github repository

[Repository](https://github.com/ziggotv)

### Thanks

-Matt Huisman for his development of the kodi addons that where used as a base for this addon

-CastagnaIt for his development of the Netflix addon that was used to steal some ideas

-peak3d for Inputstream Adaptive

-Team Kodi for Kodi
