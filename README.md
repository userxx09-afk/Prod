# Tapper apps — installable builds

This repo holds only the finished, installable builds of the Tapper apps. The
source code lives in private repos; their CI publishes here.

Each app has versioned releases (`<app>-<version>`) and one rolling release,
`<app>-latest`, whose download links never change:

| App | Install link |
| --- | --- |
| Tapper IPTV (Fire TV / Android) | https://github.com/userxx09-afk/prod/releases/download/iptv-latest/tapper-iptv.apk |
| GarysTV (Fire TV) | https://github.com/userxx09-afk/prod/releases/download/garystv-latest/GarysTV.apk |
| GarysTV (Windows) | https://github.com/userxx09-afk/prod/releases/tag/garystv-latest |
| BCN — Barb's Camera Notifications (Android) | https://raw.githubusercontent.com/userxx09-afk/prod/main/bcn/BCN.apk |
| Camera Keeper (Windows) | https://github.com/userxx09-afk/prod/releases/download/camera-keeper-windows/CameraKeeper-Setup.exe |
| Camera Keeper (Ubuntu) | https://github.com/userxx09-afk/prod/releases/download/camera-keeper-ubuntu/CameraKeeper-linux.tar.gz |
| TapperVPN | https://github.com/userxx09-afk/prod/releases/tag/vpn-latest |

BCN and Camera Keeper were called BAN (Barb's Arlo Notifications) and Arlo Keeper. `arlo/latest.json`
stays for phones still on BAN: it points at `bcn/BCN.apk`, so they update into BCN. The old
`arlo-windows-installer` and `arlo-ubuntu` releases are no longer updated.
