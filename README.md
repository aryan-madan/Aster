# Aster

![Aster](./og.png)

Aster is a browser for macOS, built with native WebKit and designed to feel calm, fast, and focused.

Browsers became too bloated and oversaturated that people forgot what they really need in a browser. Aster brings the best of both aesthetic and performance, with native WebKit and beautiful interactions.

[aster.aryan.am](https://aster.aryan.am) · Made with ❤️ by [Ary](https://aryan.am) · [https://github.com/aryan-madan/Aster.git](https://github.com/aryan-madan/Aster.git)

## Install

Download [Aster 0.2.0](https://github.com/aryan-madan/Aster/releases/download/v0.2.0/Aster.zip), unzip it, and drag `Aster.app` into your **Applications** folder.

This app is not signed or notarized with an Apple Developer ID, so macOS may block it on first launch. Only continue if you trust the person who provided the app. First try Control-clicking `Aster.app`, choosing **Open**, then confirming. If macOS still blocks it, remove its quarantine attribute in Terminal:

```sh
xattr -dr com.apple.quarantine "/Applications/Aster.app"
```

This removes quarantine metadata and bypasses Gatekeeper's first-open check; it does not check the app for malware. If you installed the app somewhere else, replace the path with its actual location. To inspect quarantine metadata, run:

```sh
xattr -lr "/Applications/Aster.app"
```

Open Aster from Applications after using either first-open method above.
