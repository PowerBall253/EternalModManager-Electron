# EternalModManager
[![Build](https://github.com/PowerBall253/EternalModManager/actions/workflows/build.yml/badge.svg)](https://github.com/PowerBall253/EternalModManager/actions/workflows/build.yml)

Cross-platform mod manager for DOOM Eternal, built with Electron.

## Installing
### Linux (Flatpak)
The app is currently available in [Flathub](https://flathub.org/apps/details/com.powerball253.eternalmodmanager). To install it, make sure you have `flatpak` installed, then run
```
flatpak install flathub com.powerball253.eternalmodmanager
```
and reboot your system. The app should now be available in your DE's menu, or you can run it in your terminal with the following command:
```
flatpak run com.powerball253.eternalmodmanager
```

### Windows (Self-contained executable)
Download the latest .exe file from the release section to your DOOM Eternal directory.

## Running
First, make sure you have the latest LTS version of NodeJS and `npm` installed. Then clone the repo, and run the following commands:

```
npm ci
npm start
```

## Compiling
First, make sure you have the latest LTS version of NodeJS and `npm` installed. Then clone the repo, and run the following commands:

```
npm ci
npm run build
```

The compiled standalone/AppImage binary will be located in the `dist` folder.
