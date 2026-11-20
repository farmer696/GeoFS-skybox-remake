GeoFS Skybox Remake

A userscript that replaces the night sky in GeoFS with a real Milky Way panorama. It's correctly oriented, rotates with the Earth, and runs on Cesium's own skybox, so it doesn't touch the rest of the rendering.

<!-- Add a screenshot: save one as docs/screenshot.png and uncomment the next line --> <!-- ![Milky Way over a jet in GeoFS](docs/screenshot.png) -->

Unofficial. Not affiliated with GeoFS, and GeoFS updates can break it.

Features
Embedded 4000 x 2000 galactic panorama, so there's nothing to host or download
True sky: the galactic center, Magellanic Clouds and dust lanes sit where they do in reality
About 80 real bright stars (Sirius, Orion, the Southern Cross...) redrawn crisply on top
Fast load: starts at page load, bakes on the GPU, and shows a quick 1024px sky before the full 2048px one
Hides itself in daylight, and falls back safely if WebGL2 or the image isn't available
Install
Install Tampermonkey (or Violentmonkey).
Open the script and click Install: geofs-skybox-remake.user.js
Hard-reload GeoFS (Ctrl+Shift+R) and fly at night.

The script is about 2.9 MB because the panorama is inside it. Needs a desktop browser with WebGL2.
