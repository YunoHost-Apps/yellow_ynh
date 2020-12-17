# Yellow for YunoHost

[![Integration level](https://dash.yunohost.org/integration/yellow.svg)](https://dash.yunohost.org/appci/app/yellow) ![](https://ci-apps.yunohost.org/ci/badges/yellow.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/yellow.maintain.svg)  
[![Install Yellow with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yellow)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Yellow quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Datenstrom Yellow is a CMS (Content management system) designed to make the creation of a website ultra-simple and easy to use. Yellow does not require a database.

**Shipped version:** 0.8.16

## Screenshots

![](https://datenstrom.se/media/images/datenstrom-yellow-en.png)

## Demo

* [Official demo](https://datenstrom.se/yellow/demo/)

## Configuration

* How to configure this app: From an admin panel.

## Documentation

 * Official documentation: https://datenstrom.se/yellow/help/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

* Are LDAP and HTTP auth supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/yellow%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/yellow/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/yellow%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/yellow/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/yellow_ynh/issues
 * App website: https://datenstrom.se/
 * Upstream app repository: https://github.com/datenstrom/yellow/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/yellow_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/yellow_ynh/tree/testing --debug
or
sudo yunohost app upgrade yellow -u https://github.com/YunoHost-Apps/yellow_ynh/tree/testing --debug
```
