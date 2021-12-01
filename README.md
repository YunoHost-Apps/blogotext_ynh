<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# BlogoText for YunoHost

[![Integration level](https://dash.yunohost.org/integration/blogotext.svg)](https://dash.yunohost.org/appci/app/blogotext) ![](https://ci-apps.yunohost.org/ci/badges/blogotext.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/blogotext.maintain.svg)  
[![Install BlogoText with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=blogotext)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install BlogoText quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

This is BlogoText, the lightweight Blog-Engine.

### Features

- Blog with comments and RSS feeds
- Links sharing
- RSS Reader
- Images/Files uploading and sharing
- JSON/ZIP/HTML import-export; WordPress import
- Support Addons


**Shipped version:** 3.7.6~ynh5

**Demo:** https://blogotext.org/blog/

## Screenshots

![](./doc/screenshots/preview.png)

## Disclaimers / important information

## Configuration

How to configure this app: by the admin panel `https://domain.tld/admin`.
## Documentation and resources

* Official app website: https://blogotext.org/
* Official admin documentation: https://github.com/BlogoText/blogotext/wiki
* Upstream app code repository: https://github.com/BlogoText/blogotext
* YunoHost documentation for this app: https://yunohost.org/app_blogotext
* Report a bug: https://github.com/YunoHost-Apps/blogotext_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing --debug
or
sudo yunohost app upgrade blogotext -u https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps