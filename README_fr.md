# BlogoText pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/blogotext.svg)](https://dash.yunohost.org/appci/app/blogotext) ![](https://ci-apps.yunohost.org/ci/badges/blogotext.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/blogotext.maintain.svg)  
[![Installer BlogoText avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=blogotext)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer BlogoText rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

This is BlogoText, the lightweight Blog-Engine.

### Features

- Blog with comments and RSS feeds
- Links sharing
- RSS Reader
- Images/Files uploading and sharing
- JSON/ZIP/HTML import-export; WordPress import
- Support Addons


**Version incluse :** 3.7.6~ynh5

**Démo :** https://blogotext.org/blog/

## Captures d'écran

![](./doc/screenshots/preview.png)

## Avertissements / informations importantes

## Configuration

How to configure this app: by the admin panel `https://domain.tld/admin`.
## Documentations et ressources

* Site officiel de l'app : https://blogotext.org/
* Documentation officielle de l'admin : https://github.com/BlogoText/blogotext/wiki
* Dépôt de code officiel de l'app : https://github.com/BlogoText/blogotext
* Documentation YunoHost pour cette app : https://yunohost.org/app_blogotext
* Signaler un bug : https://github.com/YunoHost-Apps/blogotext_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing --debug
ou
sudo yunohost app upgrade blogotext -u https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps