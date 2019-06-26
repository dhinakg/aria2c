# Aria2c for android

aria2 is a utility for downloading files. The supported protocols are HTTP(S), FTP, SFTP, BitTorrent, and Metalink. aria2 can download a file from multiple sources/protocols and tries to utilize your maximum download bandwidth. It supports downloading a file from HTTP(S)/FTP/SFTP and BitTorrent at the same time, while the data downloaded from HTTP(S)/FTP/SFTP is uploaded to the BitTorrent swarm. Using Metalink's chunk checksums, aria2 automatically validates chunks of data while downloading a file like BitTorrent. The project page is located at [https://aria2.github.io]. See aria2 Online Manual to learn how to use aria2.

## Installation
- Download [.zip module](https://github.com/Magisk-Modules-Repo/aria2c/releases), flash it in Magisk Manager App or in Recovery. Install uget download manager for android from [https://ugetdm.com/downloads/android/]. uget can be configured for download through aria2c or curl.

## Features

- Command-line interface
-   Download files through HTTP(S)/FTP/SFTP/BitTorrent
-   Segmented downloading
-   Metalink version 4 (RFC 5854) support(HTTP/FTP/SFTP/BitTorrent)
-   Metalink version 3.0 support(HTTP/FTP/SFTP/BitTorrent)
-   Metalink/HTTP (RFC 6249) support
-   HTTP/1.1 implementation
-   HTTP Proxy support
-   HTTP BASIC authentication support
-   HTTP Proxy authentication support
-   Well-known environment variables for proxy: http_proxy, https_proxy, ftp_proxy, all_proxy and no_proxy
-   HTTP gzip, deflate content encoding support
-   Verify peer using given trusted CA certificate in HTTPS
-   Client certificate authentication in HTTPS
-  Chunked transfer encoding support
-   Load Cookies from file using the Firefox3 format, Chromium/Google Chrome and the Mozilla/Firefox (1.x/2.x)/Netscape format.
-   Save Cookies in the Mozilla/Firefox (1.x/2.x)/Netscape format.
-   Custom HTTP Header support
-   Persistent Connections support
-   FTP/SFTP through HTTP Proxy
-   Download/Upload speed throttling
-   BitTorrent extensions: Fast extension, DHT, PEX, MSE/PSE, Multi-Tracker, UDP tracker
-   BitTorrent WEB-Seeding. aria2 requests chunks more than piece size to reduce the request overhead. It also supports pipelined requests with piece size.
-   BitTorrent Local Peer Discovery
-   Rename/change the directory structure of BitTorrent downloads completely
-   JSON-RPC (over HTTP and WebSocket)/XML-RPC interface
-   Run as a daemon process
-   Selective download in multi-file torrent/Metalink
-   Chunk checksum validation in Metalink
-   Can disable segmented downloading in Metalink
-   Netrc support
-   Configuration file support
-   Download URIs found in a text file or stdin and the destination directory and output file name can be specified optionally
-   Parameterized URI support
-   IPv6 support with Happy Eyeballs
-   Disk cache to reduce disk activity


## Changelog
### 0.1.0
- initial release as magisk module 

## Credit
- aria2 upstream | [aria2](https://github.com/aria2/aria2)
