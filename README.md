# Headra

**A simple, honest compass for Android.** True north by default, magnetic north with one tap, and a live GPS status panel.

No ads · No tracking · No internet · ~18 KB

[**⬇ Download Compass.apk**](Compass.apk)

---

## Features

- **True north** — corrected for the magnetic declination where you are
- **Magnetic north** — tap the heading at the top to switch, tap again to switch back
- **Live GPS status** — fix type, satellites used / in view, accuracy, signal strength
- **Position** — latitude, longitude, altitude and speed
- **Every satellite system** — GPS, Galileo, GLONASS, BeiDou, QZSS, NavIC
- **Works offline** — remembers your last declination
- **Flat or upright** — flat it follows the top of the phone; upright it follows the back camera

## Install

1. Download [`Compass.apk`](Compass.apk) on your phone.
2. Open it and allow **Install unknown apps** when asked.
3. Allow **precise location** for true north and GPS status.

Requires Android 7.0 or newer.

## Tips

- If you see **Low accuracy**, wave the phone in a figure‑8.
- Keep away from magnets, metal and other electronics.
- GPS works best outdoors with a clear view of the sky.

## Build from source

Needs JDK 17+ and the Android SDK (platform 34).

```sh
./gradlew assembleRelease
```

The APK is written to `app/build/outputs/apk/release/`.

## License

[GPL-3.0](LICENSE)
