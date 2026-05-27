# Part 107 Flight Record iPhone App

This folder is the installable iPhone web-app version of the Part 107 flight record app.

## What is included

- `index.html`: the app.
- `manifest.webmanifest`: iPhone/Home Screen app identity.
- `service-worker.js`: offline cache support when hosted from HTTPS.
- `icons/`: Home Screen icons.

## Test on this Mac

From this folder, run:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://127.0.0.1:8080
```

## Install on iPhone

For the clean iPhone install flow, host this folder on an HTTPS site such as GitHub Pages, Netlify, or Vercel.

After it is online:

1. Open the HTTPS link in Safari on the iPhone.
2. Tap Share.
3. Tap Add to Home Screen.
4. Name it Flight Record.
5. Tap Add.

The app will appear on the iPhone Home Screen like a normal app.

## App Store path

This same app can later be packaged for the Apple App Store with Capacitor. That requires:

- an Apple Developer account,
- Xcode on a Mac,
- app signing setup,
- App Store screenshots and metadata.

The installable web app is the fastest way to use it on the phone first.
