# unraid-icons

Icons for my Unraid server: animated folder icons for the Docker Folder plugin, and
logos for containers that do not ship a usable one.

## Animated Docker folder icons

The orange animated icons are from
[hernandito's unRAID Docker Folder Animated Icons](https://github.com/hernandito/unRAID-Docker-Folder-Animated-Icons---Alternate-Colors)
(the Orange Collection, which upstream has since moved to its `deprecated/` folder in
favour of the newer flat collections). All credit for them goes to hernandito. For the
current sets, use upstream.

<img src="orange-ai.svg" width=64 height=64> <img src="orange-ai2.svg" width=64 height=64> <img src="orange-audio.svg" width=64 height=64> <img src="orange-backup.svg" width=64 height=64> <img src="orange-binoculars.svg" width=64 height=64> <img src="orange-books.svg" width=64 height=64> <img src="orange-books2.svg" width=64 height=64> <img src="orange-books3.svg" width=64 height=64> <img src="orange-camera.svg" width=64 height=64> <img src="orange-chat.svg" width=64 height=64> <img src="orange-cloud.svg" width=64 height=64> <img src="orange-code.svg" width=64 height=64> <img src="orange-control.svg" width=64 height=64> <img src="orange-cooking.svg" width=64 height=64> <img src="orange-dash.svg" width=64 height=64> <img src="orange-database.svg" width=64 height=64> <img src="orange-dependencies.svg" width=64 height=64> <img src="orange-downloads.svg" width=64 height=64> <img src="orange-eye.svg" width=64 height=64> <img src="orange-finances.svg" width=64 height=64> <img src="orange-gaming.svg" width=64 height=64> <img src="orange-globe.svg" width=64 height=64> <img src="orange-grafana.svg" width=64 height=64> <img src="orange-hammer.svg" width=64 height=64> <img src="orange-home-automation.svg" width=64 height=64> <img src="orange-homeautomation2.svg" width=64 height=64> <img src="orange-jellyfin.svg" width=64 height=64> <img src="orange-multimedia.svg" width=64 height=64> <img src="orange-multimedia2.svg" width=64 height=64> <img src="orange-music.svg" width=64 height=64> <img src="orange-network.svg" width=64 height=64> <img src="orange-nzb.svg" width=64 height=64> <img src="orange-pirate.svg" width=64 height=64> <img src="orange-plex.svg" width=64 height=64> <img src="orange-productivity.svg" width=64 height=64> <img src="orange-scrape.svg" width=64 height=64> <img src="orange-search.svg" width=64 height=64> <img src="orange-security.svg" width=64 height=64> <img src="orange-settings.svg" width=64 height=64> <img src="orange-ship.svg" width=64 height=64> <img src="orange-tentative.svg" width=64 height=64> <img src="orange-tmm.svg" width=64 height=64> <img src="orange-torrent.svg" width=64 height=64> <img src="orange-vpn.svg" width=64 height=64> <img src="orange-youtube.svg" width=64 height=64> <img src="orange-youtube4.svg" width=64 height=64> <img src="orange-youtube5.svg" width=64 height=64>

Added here as needed:

- <img src="orange-3d-printing.svg" width=32 height=32> `orange-3d-printing.svg`, a 3D printing icon in the same style
- PNG copies of a few icons (`ai`, `dash`, `database`, `finances`, `search`, `ship`) for places that do not take SVG

## Container logos

Logos for containers whose templates lack an icon, taken from each project. They belong
to their respective projects. `fundbot` and `helix-viewer` are my own projects.

<img src="arralogo.svg" width=64 height=64> <img src="bl-logo.png" width=64 height=64> <img src="ezbookkeeping.png" width=64 height=64> <img src="fundbot.png" width=64 height=64> <img src="grimmory-logo.png" width=64 height=64> <img src="helix-viewer-transparent.svg" width=64 height=64> <img src="kopn%20%281%29.jpg" width=64 height=64> <img src="mmwave-logo.png" width=64 height=64> <img src="subgen-icon.png" width=64 height=64> <img src="unifi.png" width=64 height=64> <img src="voidauth-logo.png" width=64 height=64> <img src="youtube-music-icon-free-png.png" width=64 height=64>

## Using them

Point an icon field at the raw file, for example:

```
https://raw.githubusercontent.com/adman234/unraid-icons/main/orange-downloads.svg
```

`Docker.json` is my Docker Folder plugin export, which references the icons from
`/mnt/user/appdata/icons/`.
