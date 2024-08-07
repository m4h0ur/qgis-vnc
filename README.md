# Introduction 
noVNC is both a HTML VNC client JavaScript library and an application built on top of that library. noVNC runs well in any modern browser including mobile browsers (iOS and Android). It has builtin CloudCopare and QGIS for Geo purposes.

# Getting Started
docker pull ghcr.io/m4h0ur/qgis-vnc:latest

docker run -d --name noVNC-desktop -p 8790:80 -v /path/to/local/files:/path/to/local/files ghcr.io/m4h0ur/qgis-vnc:latest

If you want to try it with password when you log in, try this:

docker run -d --name noVNC-desktop -p 8790:80 -v /path/to/local/files:/path/to/local/files -e VNC_PASSWORD=YOUR_PASSWORD ghcr.io/m4h0ur/qgis-vnc:latest
