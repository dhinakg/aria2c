# The development on this repository has ceased due to probable breaking of Android's security model and adding further layers of trust where it is inappropriate by rooting (More details at [https://madaidans-insecurities.github.io/](https://madaidans-insecurities.github.io/android.html)).


# Magisk module of aria2c for android

aria2c is a utility for downloading files. The supported protocols are HTTP(S), FTP, SFTP, BitTorrent, and Metalink. aria2c can download a file from multiple sources/protocols and tries to utilize your maximum download bandwidth. It supports downloading a file from HTTP(S)/FTP/SFTP and BitTorrent at the same time, while the data downloaded from HTTP(S)/FTP/SFTP is uploaded to the BitTorrent swarm. Using Metalink's chunk checksums, aria2c automatically validates chunks of data while downloading a file like BitTorrent. The project page is located at https://aria2.github.io/.

## Installation
- Download zip module & flash it using Magisk Manager App or in Recovery. Install [uget download manager](https://ugetdm.com/downloads/android/) for android and configure  for downloading through aria2c or curl.

## Features
-    Multi-Connection Download.
-    Lightweight
-    Fully Featured BitTorrent Client.
-    Metalink Enabled.

## Changelog
### 0.1.1 - 20191014
- updated using upstream binary version 1.35.0
### 0.1.0 - 20190627
- initial release as magisk module [using upstream binary version 1.34.0]

## Credits
- [Author](https://gist.github.com/tatsuhiro-t/) of [aria2c upstream](https://github.com/aria2/aria2/releases)

