# BlogoText for YunoHost

[![](https://dash.yunohost.org/integration/blogotext.svg) ![](https://ci-apps.yunohost.org/ci/badges/blogotext.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/blogotext.maintain.svg)](https://dash.yunohost.org/appci/app/blogotext)  
[![Install BlogoText with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=blogotext)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install BlogoText quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

This is BlogoText, the lightweight Blog-Engine.

**Shipped version:** 3.7.6

## Screenshots

![](https://raw.githubusercontent.com/BlogoText/blogotext/dev/preview.png)

## Demo

* [Official demo](https://blogotext.org/blog/)

## Configuration

How to configure this app: by the admin panel `https://domain.tld/admin`.

## Documentation

 * Official documentation: https://github.com/BlogoText/blogotext/wiki
 * YunoHost documentation: https://yunohost.org/#/app_blogotext

## YunoHost specific features

#### Multi-users support

 * Are LDAP and HTTP auth supported? **No**   
 * Can the app be used by multiple users? **No** 

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/blogotext%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/blogotext/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/blogotext%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/blogotext/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

## Links

 * Report a bug: https://github.com/YunoHost-Apps/BlogoText_ynh/issues
 * App website: https://blogotext.org/
 * Upstream app repository: https://github.com/BlogoText/blogotext
 * YunoHost website: https://yunohost.org/

---

## Developers info

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing --debug
or
sudo yunohost app upgrade blogotext -u https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing --debug
```
