DEEJ UNIVERSE CREATION ENGINE — PWA v1.10

PWA INSTALL FIX BUILD

Replace the existing GitHub Pages root files with this package's files.
Important additions/fixes:
- explicit repository-relative PWA scope/start URL
- corrected icon purpose declarations
- hardened service-worker registration and offline navigation
- cache version bump so Chrome does not keep the v1.9 shell
- .nojekyll for direct static serving on GitHub Pages

After GitHub Pages redeploys:
1. Open the live HTTPS Creation Engine page in Chrome.
2. Refresh once.
3. If Chrome still shows an old v1.9 page, close the tab and reopen the live site.
4. Use Chrome's menu -> Install app / Add to Home screen.
