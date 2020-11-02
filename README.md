# Yellow CMS for YunoHost

[![Integration level](https://dash.yunohost.org/integration/yellowcms.svg)](https://dash.yunohost.org/appci/app/yellowcms) ![](https://ci-apps.yunohost.org/ci/badges/yellowcms.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/yellowcms.maintain.svg)  
[![Install Yellowcms with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=yellowcms)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Yellow CMS quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Yellow is a CMS designed to make the creation of a website ultra-simple and easy to use. Yellow CMS does not require a database.

**Shipped version:** 0.8.16

## Screenshots

![](https://datenstrom.se/media/images/datenstrom-yellow-en.png)

## Demo

* [Official demo](https://datenstrom.se/yellow/demo/)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: https://datenstrom.se/yellow/help/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

* Are LDAP and HTTP auth supported?
* Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/yellowcms%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/yellowcms/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/yellowcms%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/yellowcms/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/yellowcms_ynh/issues
 * App website: https://datenstrom.se/
 * Upstream app repository: https://github.com/datenstrom/yellow/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing --debug
or
sudo yunohost app upgrade yellowcms -u https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing --debug
```
