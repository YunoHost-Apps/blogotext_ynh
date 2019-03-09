# BlogoText for YunoHost

![blogotext_logo](sources/images/blogotext_logo.png)


[![Integration level](https://dash.yunohost.org/integration/BlogoText.svg)](https://dash.yunohost.org/appci/app/BlogoText)  
[![Install BlogoText with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=BlogoText)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install BlogoText quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

This is BlogoText, the lightweight Blog-Engine.

**Shipped version:** 3.7.6

## Screenshots

![blogotext_preview](sources/images/blogotext_preview.png)

## Demo

* [Official demo](https://blogotext.org/blog/)

## Configuration

How to configure this app: by the admin panel `https://domain.tld/admin`.

## Documentation

 * Official documentation: https://github.com/BlogoText/blogotext/wiki
 * YunoHost documentation: https://yunohost.org/#/app_blogotext

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported? no   
Can the app be used by multiple users? no  

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/BlogoText%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/BlogoText/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/BlogoText%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/BlogoText/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/BlogoText%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/BlogoText/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

**More information on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/BlogoText_ynh/issues
 * App website: https://blogotext.org/
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing --debug
or
sudo yunohost app upgrade BlogoText -u https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing --debug
```
