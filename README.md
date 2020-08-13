# Darkwire for YunoHost

[![Integration level](https://dash.yunohost.org/integration/codimd.svg)](https://dash.yunohost.org/appci/app/codimd) ![](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)  
[![Install Darkwire with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=codimd)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Darkwire quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
CodiMD is a real-time collaborative word processing web service. It uses Markdown language.

**Shipped version:** 1.6.0

## Screenshots

![](https://demo.codimd.org/screenshot.png)

## Demo

* [Official demo](https://demo.codimd.org/)

## Configuration

You can configure CodiMD by editing this file `/var/www/codimd/config.json` using the [documentation](https://github.com/codimd/server/blob/master/docs/configuration.md)

## Documentation

 * Official documentation: https://github.com/codimd/server/tree/master/docs/
 * YunoHost documentation: https://yunohost.org/#/app_codimd

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/darkwire%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/darkwire/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/darkwire%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/darkwire/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/darkwire_ynh/issues
 * Upstream app repository: https://github.com/darkwire/darkwire.io
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/darkwire_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/darkwire_ynh/tree/testing --debug
or
sudo yunohost app upgrade darkwire -u https://github.com/YunoHost-Apps/darkwire_ynh/tree/testing --debug
```
