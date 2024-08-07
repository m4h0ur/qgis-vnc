# Introduction 
noVNC is both a HTML VNC client JavaScript library and an application built on top of that library. noVNC runs well in any modern browser including mobile browsers (iOS and Android). It has builtin CloudCopare and QGIS for Geo purposes.

Many companies, projects and products have integrated noVNC inclu
# Getting Started
docker pull ghcr.io/m4h0ur/qgis-vnc:latest

docker run -d --name qgis-desktop -p 8790:80 -v /path/to/local/files:/path/to/local/files ghcr.io/m4h0ur/qgis-vnc:latest
