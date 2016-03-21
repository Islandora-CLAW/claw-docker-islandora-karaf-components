# Islandora CLAW: Islandora Karaf Components Docker Image

[![Docker Stars](https://img.shields.io/docker/stars/islandora-claw/islandora-karaf-compontents.svg)](https://hub.docker.com/r/islandora-claw/islandora-karaf-compontents/)
[![Docker Pulls](https://img.shields.io/docker/pulls/islandora-claw/islandora-karaf-compontents.svg)](https://hub.docker.com/r/islandora-claw/islandora-karaf-compontents/)
[![Image Size](https://img.shields.io/imagelayers/image-size/islandora-claw/islandora-karaf-compontents/latest.svg)](https://imagelayers.io/?images=islandora-claw/islandora-karaf-components:latest)
[![Image Layers](https://img.shields.io/imagelayers/layers/islandora-claw/islandora-karaf-compontents/latest.svg)](https://imagelayers.io/?images=islandora-claw/islandora-karaf-components:latest)

### Introduction

Defines the Islandora Karaf Components Docker image.

Based on the
[Karaf Docker Image](https://github.com/Islandora-CLAW/docker-karaf).

### Includes

* Karaf 4
* Java 8
* Maven 3

### Build Arguments

No build arguments are provided.

### Environment Variables

This image provides no environment variables.

Please consult the
[parent image](https://github.com/Islandora-CLAW/docker-tomcat).

**Example (foreground, port 8181, auto-remove):**
```bash
docker run --rm -ti -p 8181:8181 islandora-claw/karaf
```

### Commands

For convenience a number of commands are provided in the [commands](/commands)
folder.

| Command | Arguments | Defaults | Notes                                       |
|---------|-----------|----------|---------------------------------------------|
| build   |           |          | Build this image with the default settings. |

### Notes

Eventually we will support running on either Open JDK or Oracle JDK, but
for the moment it only supports Open JDK.

### Maintainers/Sponsors

* UPEI
* discoverygarden inc.
* LYRASIS
* McMaster University
* University of Limerick
* York University
* University of Manitoba
* Simon Fraser University
* PALS
* American Philosophical Society
* common media inc.

Current maintainers:

* [Nigel Banks](https://github.com/nigelgbanks)

### Development

If you would like to contribute, please get involved with the
[Islandora Fedora 4 Interest Group](https://github.com/Islandora/Islandora-Fedora4-Interest-Group).
We love to hear from you!

If you would like to contribute code to the project, you need to be covered by
an Islandora Foundation
[Contributor License Agreement](http://islandora.ca/sites/default/files/islandora_cla.pdf)
or
[Corporate Contributor Licencse Agreement](http://islandora.ca/sites/default/files/islandora_ccla.pdf).
Please see the [Contributors](http://islandora.ca/resources/contributors) pages
on Islandora.ca for more information.

### License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
