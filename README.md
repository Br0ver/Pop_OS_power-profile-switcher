# Power Profile Switcher for PopOS
GNOME Shell extension to automatically switch between power profiles based on power supply.
This for is updated to work with Pop!OS 22.04

## Settings
![Settings window](.github/img/settings.png)

When enabled, the extension will automatically switch to:
- the selected defaults profiles based on the which power supply the device is running on.
- to power saving profile if running on battery and the percentage drops below the selected level.

## Installation

### Dependencies
This extension depends on system76-power


### From Gnome Extensions store
tbd

[<img src=".github/img/store.png" height="100" alt="Get it on GNOME Extensions">](https://extensions.gnome.org/extension/5575/power-profile-switcher/)

### Installation from source
Clone the repo, pack and install the extension.
```
git clone https://github.com/eliapasquali/power-profile-switcher
cd power-profile-switcher
gnome-extensions pack --extra-source=ui
gnome-extensions install power-profile-switcher@eliapasquali.github.io.shell-extension.zip
```
After this, the extensions is installed. In order to enable it run the following command or use the Extensions app.
```
gnome-extensions enable power-profile-switcher@eliapasquali.github.io
```

## GNOME Version Support
tbd

## Contribution
Contribution to this project are welcome
