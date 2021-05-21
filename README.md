# Miniflux for YunoHost

[![Integration level](https://dash.yunohost.org/integration/miniflux.svg)](https://dash.yunohost.org/appci/app/miniflux) ![](https://ci-apps.yunohost.org/ci/badges/miniflux.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/miniflux.maintain.svg)  
[![Install Miniflux with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=miniflux/)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Miniflux quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Miniflux is a minimalist and opinionated feed reader.

**Shipped version:** 2.0.30

## Screenshots

![](https://miniflux.app/images/overview.png)

## Configuration

You can also configure Miniflux by editing this file `/var/www/miniflux/miniflux.conf` using the [documentation](https://miniflux.app/docs/configuration.html).

## Documentation

 * Official documentation: https://miniflux.app/docs/index.html

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **No**
* Can the app be used by multiple users? **No**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/miniflux.svg)](https://ci-apps.yunohost.org/ci/apps/miniflux/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/miniflux.svg)](https://ci-apps-arm.yunohost.org/ci/apps/miniflux/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/miniflux_ynh/issues
 * Upstream app repository: https://github.com/miniflux/v2
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/miniflux_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/miniflux_ynh/tree/testing --debug
or
sudo yunohost app upgrade miniflux -u https://github.com/YunoHost-Apps/miniflux_ynh/tree/testing --debug
```
