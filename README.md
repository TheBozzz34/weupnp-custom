# weupnp

A custom version of the lightweight Java library weupnp designed to implement the UPnP protocol and handle
port mappings on Gateway Devices. This project contains specific updates in order to better work with my project [UPnP](https://github.com/TheBozzz34/UPnP), a Minecraft plugin to open UPnP ports automatically.

You can find more information on the library at the project website:
http://bitletorg.github.io/weupnp/

Thr project is hosted on GitHub packages, you are free to download and use it for yourself, if you really really want to use my fork.

Changes:

- Added in `discoverLocalIp` method, which allows for discovering UPnP devices on a specific InetAddress
- Changed POM to be able to build the project on modern Java versions

