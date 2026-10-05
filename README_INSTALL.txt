DEEJ UNIVERSE CREATION ENGINE — PWA v1.9

This package is ready to be served from an HTTPS static host.

INSTALL ON ANDROID:
1. Upload the CONTENTS of this folder to an HTTPS static web host.
2. Open the resulting HTTPS address in Chrome on Android.
3. Chrome menu (three dots) -> Install app / Add to Home screen.
4. Launch Deej Universe from its home-screen icon.
5. Open it once while online so the service worker caches the shell.
6. It can then launch offline.

IMPORTANT:
Opening index.html directly from Downloads/content:// will NOT enable the service worker or true PWA installation.
The app's data remains browser-local. Before changing host/domain or clearing browser site data, export a JSON backup from the engine.
