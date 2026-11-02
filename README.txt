JARVIS Voice Assistant - lightweight JavaScript PWA source

Included:
- index.html: complete UI and JavaScript voice assistant
- manifest.json: installable app metadata
- sw.js: offline cache

IMPORTANT:
This is a JavaScript web app source, not an APK. Android cannot install a ZIP/HTML file directly as a native app.
To install it as a standalone home-screen app, the files must be hosted on an HTTPS site, then open the site on your tablet and use the browser menu > Install app / Add to Home screen. It will launch in its own app window, not a normal browser tab.
Microphone support depends on Android speech recognition service and permission. Voice features may not work when opening index.html directly from File Manager.
This starter handles common commands locally. Open-ended AI requires a secure backend/API connection; do not place a private API key in client-side JavaScript.
