# rxenv

My home setup: the media server, the TV apps and the launcher I built around it. Each piece lives in its own repo.

| Project | What it is |
|---|---|
| [RxFilms server](https://github.com/RexSAS/RxFilms) | `rexserver`: Jellyfin + Seerr behind nginx and Cloudflare, with the audit and tuning notes (VA-API transcoding, BBR, mergerfs, DDNS). |
| [RxFilms for FireStick](https://github.com/RexSAS/RxFilms-Tv-AppInstaller) | Customized Jellyfin Android TV app (home rows, Seerr requests, SyncPlay, in-app updates), plus a phone app that installs it on the TV. |
| [RxFilms for LG Smart TV](https://github.com/RexSAS/RxFilms-Tv-AppInstaller/tree/main/RxFilms%20For%20Lg%20Smart%20TV) | The same RxFilms experience as a webOS app (webOS 4+), plain JavaScript with a small on-TV service for Seerr calls. |
| [rxhome-tv](https://github.com/RexSAS/rxhome-tv) | Custom Android TV launcher: app grid, RxFilms rows from Jellyfin, now-playing with synced lyrics, ClaudeFm, red-key shortcut. |
| [OpenWRT-Backup](https://github.com/RexSAS/OpenWRT-Backup) *(private)* | OpenWRT + WireGuard config for the Raspberry Pi Zero 2 W router/VPN. |
