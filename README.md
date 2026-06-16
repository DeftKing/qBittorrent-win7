qBittorrent - A BitTorrent client in Qt
------------------------------------------
### Description:
qBittorrent is a bittorrent client programmed in C++ / Qt that uses
libtorrent (sometimes called libtorrent-rasterbar) by Arvid Norberg.

It aims to be a good alternative to all other bittorrent clients
out there. qBittorrent is fast, stable and provides unicode
support as well as many features.

The free [IP to Country Lite database](https://db-ip.com/db/download/ip-to-country-lite) by [DB-IP](https://db-ip.com/) is used for resolving the countries of peers. The database is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

### About this fork:

Builded with a backport of the Qt 6 qtbase module, tailored for compatibility with Windows 7, 8 and 8.1 (https://github.com/crystalidea/qt6windows7).

Many of other Qt 6 modules are known to work fine on Windows 7 without modifications when compiled with patched qtbase. Verified modules:
qt5compat
qtimageformats
qttools
... please let me know which work and which don't !

Known issues:
QRhi using DirectX 11/12 is not ported
So themes won't work...

### Misc:
For more information please visit:
https://www.qbittorrent.org

or our wiki here:
https://wiki.qbittorrent.org

Use the forum for troubleshooting before reporting bugs:
https://forum.qbittorrent.org

Please report any bug (or feature request) to:
https://bugs.qbittorrent.org

Official IRC channel:
[#qbittorrent on irc.libera.chat](ircs://irc.libera.chat:6697/qbittorrent)
