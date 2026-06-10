# Awesome Wallpaper Engine [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated tools, integrations, documentation, and resources for Wallpaper Engine, the live-wallpaper app for Windows and macOS.

Wallpaper Engine lets you run animated, interactive, audio-reactive, and web-based wallpapers on your desktop. This list collects the open-source tooling and community knowledge built around it: asset extractors, creation references, desktop integrations, Linux players, and notable open-source alternatives.

This is an unofficial, community-maintained list and is not affiliated with the Wallpaper Engine developers.

## Contents

- [Official](#official)
- [Documentation](#documentation)
- [Community guides & tutorials](#community-guides--tutorials)
- [Asset extraction & conversion](#asset-extraction--conversion)
- [Workshop downloaders](#workshop-downloaders)
- [Creation tools & web wallpapers](#creation-tools--web-wallpapers)
- [Color sync & theming](#color-sync--theming)
- [Music & now playing](#music--now-playing)
- [RGB lighting & Rainmeter](#rgb-lighting--rainmeter)
- [Automation, CLI & Stream Deck](#automation-cli--stream-deck)
- [OBS & streaming](#obs--streaming)
- [Linux](#linux)
  - [Run Wallpaper Engine content](#run-wallpaper-engine-content)
  - [GUIs & frontends](#guis--frontends)
  - [Wayland](#wayland)
- [Open-source alternatives](#open-source-alternatives)
  - [Windows](#windows)
  - [macOS](#macos)
  - [Linux (see also)](#linux-see-also)
- [Workshop collections](#workshop-collections)

## Official

- [Steam Workshop for Wallpaper Engine](https://steamcommunity.com/app/431960/workshop/) - Official hub for discovering and sharing wallpapers.
- [Wallpaper Engine on Steam](https://store.steampowered.com/app/431960/Wallpaper_Engine/) - Official store page for the paid Windows and macOS app.
- [Wallpaper Engine for Android](https://www.wallpaperengine.io/android) - Free official companion app to view your collection on Android.
- [Wallpaper Engine website](https://www.wallpaperengine.io/) - Official product site with features, help, and documentation links.

## Documentation

- [Audio visualization API](https://docs.wallpaperengine.io/en/web/audio/visualizer.html) - The `wallpaperRegisterAudioListener` API for audio-reactive web wallpapers.
- [Designer documentation](https://docs.wallpaperengine.io/) - Official creator docs hub for Scene, Web, and Video wallpapers.
- [Getting started with your first wallpaper](https://docs.wallpaperengine.io/en/scene/first/gettingstarted.html) - Beginner walkthrough of the Scene editor.
- [Help & FAQ](https://help.wallpaperengine.io/) - Official troubleshooting, performance, and multi-monitor help.
- [Media integration API](https://docs.wallpaperengine.io/en/web/audio/media.html) - Now-playing title, artist, and thumbnail listeners for web wallpapers.
- [Publishing to the Steam Workshop](https://docs.wallpaperengine.io/en/scene/first/publishing.html) - How to package and publish a finished wallpaper.
- [RGB hardware API](https://docs.wallpaperengine.io/en/web/api/rgb.html) - Drive RGB peripherals and iCUE devices from a web wallpaper.
- [SceneScript reference](https://docs.wallpaperengine.io/en/scene/scenescript/reference.html) - Full API for the JavaScript-like scripting language used in Scene wallpapers.
- [Shader programming overview](https://docs.wallpaperengine.io/en/scene/shader/overview.html) - Writing custom GLSL image-effect shaders in the editor.
- [wallpaperPropertyListener API](https://docs.wallpaperengine.io/en/web/api/propertylistener.html) - JavaScript callbacks for user properties and pause state.
- [Web wallpaper reference](https://docs.wallpaperengine.io/en/web/overview.html) - Entry point for building HTML, CSS, and JS wallpapers.

## Community guides & tutorials

- [Audio Responsive Bar SceneScript](https://steamcommunity.com/sharedfiles/filedetails/?id=1760471017) - Steam guide for building audio-reactive bars with SceneScript.
- [Creating an HTML web wallpaper](https://steamcommunity.com/sharedfiles/filedetails/?id=770801435) - Steam guide to setting up and publishing a web wallpaper.
- [Getting started with Wallpaper Engine](https://steamcommunity.com/sharedfiles/filedetails/?id=768427357) - Top-rated Steam guide comparing the four wallpaper types.
- [Guide to create a web-based audio visualizer](https://steamcommunity.com/sharedfiles/filedetails/?id=876122363) - Steam guide for an HTML5-canvas audio visualizer.
- [r/wallpaperengine](https://www.reddit.com/r/wallpaperengine/) - Main community subreddit for sharing wallpapers and troubleshooting.

## Asset extraction & conversion

- [ilgnefz/we_repkg](https://github.com/ilgnefz/we_repkg) - Cross-platform GUI extractor built on RePKG.
- [notscuffed/repkg](https://github.com/notscuffed/repkg) - Command-line PKG extractor and TEX-to-image converter; the de facto standard.
- [TheRioMiner/Wallpaper-Engine-Pkg-to-Zip](https://github.com/TheRioMiner/Wallpaper-Engine-Pkg-to-Zip) - Convert Wallpaper Engine `.pkg` files to `.zip` and back.
- [trinityhades/WallpaperExtractor](https://github.com/trinityhades/WallpaperExtractor) - macOS project downloader and `.pkg` extractor.

## Workshop downloaders

Use these to back up wallpapers you own or to fetch assets for the Linux players below. Respect the Steam Subscriber Agreement, honor creators' rights, and buy Wallpaper Engine to support its developers.

- [ArtyomArtamonov/wallpaper-engine-downloader](https://github.com/ArtyomArtamonov/wallpaper-engine-downloader) - Install wallpapers into the Wallpaper Engine folder from a Workshop link (archived).
- [SteamAutoCracks/WallpaperEngineWorkshopDownloader](https://github.com/SteamAutoCracks/WallpaperEngineWorkshopDownloader) - Popular DepotDownloader-based Workshop item downloader.

## Creation tools & web wallpapers

- [aleab/acav-we](https://github.com/aleab/acav-we) - Highly customizable audio visualizer web wallpaper.
- [ChenYCL/single-html](https://github.com/ChenYCL/single-html) - Bundle images and Marmoset 3D models into a single-file web wallpaper.
- [CSaratakij/Rive2WallpaperEngineTemplate](https://github.com/CSaratakij/Rive2WallpaperEngineTemplate) - Template for importing Rive animations as web wallpapers.
- [hexxone/audiorbits](https://github.com/hexxone/audiorbits) - Open-source audio-reactive WebGL wallpaper for Wallpaper Engine and Lively.
- [linsyking/CanvasHelper](https://github.com/linsyking/CanvasHelper) - Canvas-based web wallpaper framework (archived).
- [spicy-wolf/spine-wallpaper-engine](https://github.com/spicy-wolf/spine-wallpaper-engine) - Spine animation player for web wallpapers (archived).

## Color sync & theming

- [brendanwelsh/yasb-wallpaper-engine-color-sync](https://github.com/brendanwelsh/yasb-wallpaper-engine-color-sync) - Tint your YASB bar and Windows taskbar to match the active wallpaper.

## Music & now playing

- [evaera/wallpaper-engine-spotify-helper](https://github.com/evaera/wallpaper-engine-spotify-helper) - Local helper that forwards Spotify now-playing data to web wallpapers.
- [secchanu/spotify-wallpaper](https://github.com/secchanu/spotify-wallpaper) - Web wallpaper showing the current Spotify track and album art.

## RGB lighting & Rainmeter

- [qiangqiang101/OpenRGB-Wallpaper-Engine](https://github.com/qiangqiang101/OpenRGB-Wallpaper-Engine) - Expose your wallpaper as an OpenRGB device to sync lighting.
- [tjhrulz/MessagePassingForRainmeter](https://github.com/tjhrulz/MessagePassingForRainmeter) - WebSocket plugin for passing messages between Rainmeter and Wallpaper Engine.

## Automation, CLI & Stream Deck

- [Command-line controls](https://help.wallpaperengine.io/en/functionality/cli.html) - Official CLI reference for scripting wallpapers, playlists, and properties.
- [DavisSolomon/Stream-Deck-Wallpaper-Engine](https://github.com/DavisSolomon/Stream-Deck-Wallpaper-Engine) - Switch wallpapers from an Elgato Stream Deck button.
- [L1nexi/Context-Aware-Wallpaper-Engine-Scheduler](https://github.com/L1nexi/Context-Aware-Wallpaper-Engine-Scheduler) - Schedule playlists by time, weather, and active window.

## OBS & streaming

- [Use Wallpaper Engine as an OBS background](https://steamcommunity.com/app/431960/discussions/2/135511379838150793/) - Developer-endorsed method using "Play in window" with OBS Game Capture.

## Linux

### Run Wallpaper Engine content

- [Almamu/linux-wallpaperengine](https://github.com/Almamu/linux-wallpaperengine) - Core engine that runs real Wallpaper Engine Workshop content on Linux (X11 and wlroots).
- [catsout/wallpaper-engine-kde-plugin](https://github.com/catsout/wallpaper-engine-kde-plugin) - KDE Plasma plugin for Wallpaper Engine wallpapers (archived but widely used).

### GUIs & frontends

- [anufrievroman/waypaper](https://github.com/anufrievroman/waypaper) - Wayland and X11 wallpaper manager with a linux-wallpaperengine backend.
- [AzPepoze/linux-wallpaperengine-gui](https://github.com/AzPepoze/linux-wallpaperengine-gui) - Go and Electron GUI for linux-wallpaperengine.
- [Maxnights/simple-linux-wallpaperengine-gui](https://github.com/Maxnights/simple-linux-wallpaperengine-gui) - Simple GUI frontend for linux-wallpaperengine.
- [MikiDevLog/wallpaperengine-gui](https://github.com/MikiDevLog/wallpaperengine-gui) - C++ GUI for linux-wallpaperengine.
- [slynobody/linux_wallpaper_engine__precompiled](https://github.com/slynobody/linux_wallpaper_engine__precompiled) - Precompiled linux-wallpaperengine builds for common distros.
- [YangYuS8/lwe](https://github.com/YangYuS8/lwe) - Tauri desktop app to browse, manage, and apply content (Hyprland and niri focus).

### Wayland

- [hack3rmann/waywe-rs](https://github.com/hack3rmann/waywe-rs) - Wallpaper Engine-style player for Wayland, written in Rust.
- [mechakotik/openwallpaper](https://github.com/mechakotik/openwallpaper) - Interactive live wallpapers for Wayland, inspired by Wallpaper Engine.
- [ZreXoc/waywe](https://github.com/ZreXoc/waywe) - Plays Wallpaper Engine videos through mpvpaper on Wayland.

## Open-source alternatives

Not Wallpaper Engine itself, but free and open-source live-wallpaper apps worth knowing about.

### Windows

- [Francesco149/weebp](https://github.com/Francesco149/weebp) - Minimal engine to set any window or video as a wallpaper (stale).
- [GiantappMan/livewallpaper](https://github.com/GiantappMan/livewallpaper) - Live and static wallpaper app for Windows 10/11 with a built-in community.
- [kelteseth/ScreenPlay](https://gitlab.com/kelteseth/ScreenPlay) - Cross-platform live wallpaper, widgets, and app drawer; also free on Steam.
- [rocksdanister/lively](https://github.com/rocksdanister/lively) - Lively Wallpaper, the leading free alternative (video, web, shader, GIF).
- [SegoCode/AutoWall](https://github.com/SegoCode/AutoWall) - Live wallpapers on Windows 7 through 11, including from the Steam Workshop.
- [Taiizor/Sucrose](https://github.com/Taiizor/Sucrose) - Versatile interactive wallpaper engine for Windows.

### macOS

- [fatihkan/wallnetic](https://github.com/fatihkan/wallnetic) - Cinematic 4K video wallpapers built with SwiftUI and Metal.
- [jipika/WaifuX](https://github.com/jipika/WaifuX) - Wallhaven, MotionBG, and anime live wallpapers for macOS.
- [nhiroyasu/wallpaper-play](https://github.com/nhiroyasu/wallpaper-play) - Live wallpaper app for macOS.

### Linux (see also)

- [christianloopp/komorebi](https://github.com/christianloopp/komorebi) - GNOME live-wallpaper app with parallax and video (not the Windows tiling WM).
- [GhostNaN/mpvpaper](https://github.com/GhostNaN/mpvpaper) - Video wallpaper program for wlroots Wayland compositors.
- [LGFae/swww](https://github.com/LGFae/swww) - Animated-transition wallpaper daemon for Wayland (archived).

## Workshop collections

- [PositivePressure's Wallpaper Engine Collection](https://steamcommunity.com/sharedfiles/filedetails/?id=2801058904) - Hand-curated "best of" collection of 327 wallpapers with 16k+ favorites.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](contributing.md) first, then open a pull request. Every entry must point to a resource that is genuinely about Wallpaper Engine and must resolve to a live page.

---

To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) (CC0 1.0 Universal).
