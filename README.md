# Introduction 
TODO: Give a short introduction of your project. Let this section explain the objectives or the motivation behind this project. 

# Getting Started
docker pull ghcr.io/m4h0ur/qgis-vnc:latest

docker run -d --name qgis-desktop -p 8790:80 -v /path/to/local/files:/path/to/local/files ghcr.io/m4h0ur/qgis-vnc:latest
