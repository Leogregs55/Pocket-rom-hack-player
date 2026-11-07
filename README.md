# Pocket ROM Hack Player

A phone-friendly Game Boy / Game Boy Color / Game Boy Advance player with a built-in IPS/UPS/BPS patcher, meant to be added to your home screen as a web app.

- Front end and cores: [EmulatorJS](https://emulatorjs.org) 4.2.3 with the mGBA and Gambatte libretro cores (`data/`), licensed GPL-3.0 (see `LICENSE`). Core builds come from https://github.com/EmulatorJS/build.
- `index.html`: the launcher, library, patcher and layout code.
- No game files are included or distributed. Bring your own ROMs and patches.

## Use
Open the site in Safari (iOS) or Chrome (Android) → Share → **Add to Home Screen**. Launch it from the icon for a full-screen app. Games and saves are stored on the device by the browser; use **⋯ → Export save** and the in-game **Import Save File** to move saves between devices.
