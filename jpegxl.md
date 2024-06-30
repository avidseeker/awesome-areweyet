---
title: JPEG XL support status
date: 2023-08-25
tags:
 - tracker
---

This is an issue tracker for software with no support for JPEG XL. Check [this list](https://github.com/libjxl/libjxl/blob/main/doc/software_support.md)
and the [Arch Wiki](https://wiki.archlinux.org/title/JPEG_XL#Support) for supported software.

## Browsers
* Chromium: behind a flag from version 91 to 109, [tracking bug](https://bugs.chromium.org/p/chromium/issues/detail?id=1178058)
* Firefox: behind a flag since version 90, [tracking bug](https://bugzilla.mozilla.org/show_bug.cgi?id=1539075)
* Safari: supported since version 17 beta [release notes](https://developer.apple.com/documentation/safari-release-notes/safari-17-release-notes), [tracking bug](https://bugs.webkit.org/show_bug.cgi?id=208235)
* Edge: behind a flag since version 91, start with `.\msedge.exe --enable-features=JXL`
* Opera: behind a flag since version 77.

## Software
* [Pillow](https://github.com/python-pillow/Pillow/issues/4247): (2019-12-04) Python image library many projects depend on for correct rendering.
	+ [Ueberzug](https://github.com/ueber-devel/ueberzug/issues/17): depends on Pillow.
* [libgd](https://github.com/libgd/libgd/issues/699)
* [VSCode](https://github.com/microsoft/vscode/issues/191376)

Photo editors:
* [Kolourpaint](https://bugs.kde.org/show_bug.cgi?id=462109): (2022-11-21)
* [Photopea](https://github.com/photopea/photopea/issues/5957): (2023-08-13) pending browser support.

Image viewers:
* [PowerToys](https://github.com/microsoft/PowerToys/issues/21814)
* [ImageGlass](https://github.com/d2phap/ImageGlass/issues/940)

Wallpapers:
* [xwallpaper](https://github.com/stoeckmann/xwallpaper/issues/48)

Websites:
* [PixelFed](https://github.com/pixelfed/pixelfed/issues/3102): (2021-12-29)
* [Mastodon](https://github.com/mastodon/mastodon/issues/20896): (2022-11-16)
* [Lemmy](https://github.com/LemmyNet/lemmy/issues/3282): (2023-06-23)
* [Wordpress](https://github.com/WordPress/performance/issues/12)

Documents:
* [Libreoffice](https://bugs.documentfoundation.org/show_bug.cgi?id=156931): (2023-08-26)
* [Marktext](https://github.com/marktext/marktext/issues/3671): (2023-08-27)
* [Ghostwriter](https://bugs.kde.org/show_bug.cgi?id=473776): (2023-08-26)

PDF:
* [Ghostscript](https://bugs.ghostscript.com/show_bug.cgi?id=703844): (2021-05-11)
* [SumatraPDF](https://github.com/sumatrapdfreader/sumatrapdf/issues/1943): (2021-05-10)
* [Foliate](https://github.com/johnfactotum/foliate/issues/1193)

Metadata:
* [Exiftool](https://github.com/exiftool/exiftool/issues/157): not all metadata supported.
* [libjxl](https://github.com/libjxl/libjxl/issues/1806): support uncompressed metadata encoding

## Android
* [AOSP Gallery](https://issuetracker.google.com/issues/259900694)
* [Simple Gallery](https://github.com/SimpleMobileTools/Simple-Gallery/issues/2669)
* [Ionut's Gallery](https://github.com/IacobIonut01/Gallery/issues/145)
* [Aves](https://github.com/deckerst/aves/issues/56)
* [Material Files](https://github.com/zhanghai/MaterialFiles/issues/995)
* [Amaze File Manager](https://github.com/TeamAmaze/AmazeFileUtilities/issues/124)
* [Kotatsu](https://github.com/KotatsuApp/Kotatsu/issues/606)

## Messaging apps
* [Signal](https://community.signalusers.org/t/50331)
* [Telegram Desktop](https://github.com/telegramdesktop/tdesktop/pull/25572)
* [Matrix](https://github.com/matrix-org/matrix-spec-proposals/pull/4030)
* [FluffyChat](https://github.com/krille-chan/fluffychat/issues/547)
* [Element.io](https://github.com/vector-im/element-meta/discussions/2023)
* Telegram iOS
* Telegram Android

## Misc bugs
* [jxlviewer](https://github.com/oupson/jxlviewer/issues/26): not associated with image/jxl mimetype.

## Supported
* [nsxiv](https://codeberg.org/nsxiv/nsxiv)
* Librewolf: [Enabled by default](https://gitlab.com/librewolf-community/browser/source/-/merge_requests/53)
* [The Lounge](https://github.com/thelounge/thelounge/pull/4219)
