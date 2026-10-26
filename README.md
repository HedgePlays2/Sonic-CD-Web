# Sonic CD Web

A web version of **Sonic CD**, originally made by Crush Arcade.

**Play online:** https://hedgeplays2.github.io/Sonic-CD-Web/

## Controls

### Keyboard
- **Arrow keys:** Move
- **Z, X, or C:** Jump
- **Enter:** Start / confirm

### Touch controls
- On-screen directional buttons for movement
- **JUMP** sends the **X** key and holds it briefly so the game can register the tap
- **START** sends **Enter**

The START button is positioned beneath JUMP for easier use on touchscreens.

## Install as an app

This site includes Progressive Web App (PWA) support. Open the site in a supported browser and choose **Install app** or **Add to Home Screen** from the browser menu. It opens in its own app window when installed.

The service worker caches the app shell so the site can open offline, but the game engine and its large game-data files are hosted remotely. **The full game is not guaranteed to work offline**, especially before its required files have loaded.

## Credits

The original web port was made by **Crush Arcade**. This repository hosts the web version and additional adjustments, including touchscreen controls and PWA support.
