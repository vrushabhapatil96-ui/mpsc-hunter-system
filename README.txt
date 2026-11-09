MPSC Hunter System v1.0

Files:
- index.html: app
- manifest.webmanifest, sw.js, icon-*.png: install/offline support

Important:
The app stores data in browser localStorage on the device/browser profile. Export a JSON backup regularly.
To install as an Android home-screen app with offline support, host these files over HTTPS, open the URL in Chrome, then use menu > Add to Home screen / Install app.
Opening index.html directly from Downloads works for basic use, but service-worker/offline installation may not be available.
This package is a PWA, not a native APK.
