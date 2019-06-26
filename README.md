# Aria2c for android

aria2 is a utility for downloading files. The supported protocols are HTTP(S), FTP, SFTP, BitTorrent, and Metalink. aria2 can download a file from multiple sources/protocols and tries to utilize your maximum download bandwidth. It supports downloading a file from HTTP(S)/FTP/SFTP and BitTorrent at the same time, while the data downloaded from HTTP(S)/FTP/SFTP is uploaded to the BitTorrent swarm. Using Metalink's chunk checksums, aria2 automatically validates chunks of data while downloading a file like BitTorrent. The project page is located at [https://aria2.github.io]. See aria2 Online Manual to learn how to use aria2.

## Installation
- Download [.zip module](https://github.com/Magisk-Modules-Repo/aria2c/releases), flash it in Magisk Manager App or in Recovery. Install uget download manager for android from [https://ugetdm.com/downloads/android/]. uget can be configured for download through aria2c or curl.

## Features

-    Multi-Connection Download. aria2 can download a file from multiple sources/protocols and tries to utilize your maximum download bandwidth. Really speeds up your download experience.

-    Lightweight. aria2 doesn’t require much memory and CPU time. When disk cache is off, the physical memory usage is typically 4MiB (normal HTTP/FTP downloads) to 9MiB (BitTorrent downloads). CPU usage in BitTorrent with download speed of 2.8MiB/sec is around 6%.

-    Fully Featured BitTorrent Client. All features you want in BitTorrent client are available: DHT, PEX, Encryption, Magnet URI, Web-Seeding, Selective Downloads, Local Peer Discovery and UDP tracker.

-    Metalink Enabled. aria2 supports The Metalink Download Description Format [aka Metalink v4](http://tools.ietf.org/html/rfc5854)), Metalink version 3 and [Metalink/HTTP](http://tools.ietf.org/html/rfc6249) . Metalink offers the file verification, HTTP/FTP/SFTP/BitTorrent integration and the various configurations for language, location, OS, etc.

-    Remote Control. aria2 supports RPC interface to control the aria2 process. The supported interfaces are JSON-RPC (over HTTP and WebSocket) and XML-RPC.



## Changelog
### 0.1.0 - 20190626
- initial release as magisk module 

## Credit
- aria2 upstream | [aria2](https://github.com/aria2/aria2)

