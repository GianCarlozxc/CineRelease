# Cine for Windows

[Download the latest Windows installer](https://github.com/GianCarlozxc/CineRelease/releases/latest)

Run **Cine-Setup-0.1.7.exe** from the release assets. Setup creates Cine shortcuts on your desktop and Start menu and launches Cine when installation finishes.

Cine includes movies, TV shows, Anime, Cartoons, Filipino films and K-drama, genre/year filters, season and episode dialogs, playback controls, resume history, caching, and dark/light themes.

Checksums are included in each release as **SHA256SUMS.txt**.

The application source and build instructions are in [GianCarlozxc/Cine](https://github.com/GianCarlozxc/Cine). This repository holds the Windows releases.

Cine 0.1.1 adds in-app updates. Install it once if you are using 0.1.0. Future versions can be detected, downloaded and installed through Cine Settings, with Update now or Later choices.

Cine 0.1.2 adds Monsters: The Lyle and Erik Menendez Story as a standalone TV entry with its poster and all nine episode choices. Open TV shows or search Menendez after updating.

Cine 0.1.3 fixes Menendez playback mapping and detects provider media-unavailable messages so Cine can try the next source automatically. Actual stream availability depends on the embedded service.

Cine 0.1.4 adds a Video quality selector to the Cine playback bar: Auto and the resolutions exposed by the current video player, including 1080p and 4K when available.

Cine 0.1.5 fixes stuck startup detection and recovery from HTTP errors. It does not resolve unavailable or rejecting external streaming services.

Cine 0.1.6 adds a separate **Free films** collection with Big Buck Bunny and Sintel, streamed directly from Internet Archive without an account or API key. Cine provides its own controls, available file resolutions, fullscreen and resume history. Both films are Blender Foundation open movies under Creative Commons Attribution 3.0. This collection does not provide access to Netflix series or repair the external providers used by other catalog entries.

Cine 0.1.7 limits total playback startup to 45 seconds, including preparation and automatic fallback. It adds a countdown, Cancel and Next player, handles empty results immediately, and prevents canceled replies from interfering with retries. VidFast is tried first; unresolved Vidking hosts have been removed. This fixes loading/recovery behavior; Menendez playback remains unavailable in the completed live provider tests.
