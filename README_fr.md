# BlogoText pour YunoHost

[![](https://dash.yunohost.org/integration/blogotext.svg) ![](https://ci-apps.yunohost.org/ci/badges/blogotext.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/blogotext.maintain.svg)](https://dash.yunohost.org/appci/app/blogotext)  
[![Install BlogoText with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=blogotext)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer BlogoText rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Ceci est BlogoText, un moteur de blog léger.

**Version incluse :** 3.7.6

## Captures d'écran

![](https://raw.githubusercontent.com/BlogoText/blogotext/dev/preview.png)

## Démo

* [Démo officielle](https://blogotext.org/blog/)

## Configuration

Comment configurer cette application: via le panneau d'administration `https://domain.tld/admin`.

## Documentation

 * Documentation officielle : https://github.com/BlogoText/blogotext/wiki
 * Documentation YunoHost : https://yunohost.org/#/app_blogotext_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

 * L'authentification LDAP et HTTP est-elle prise en charge ? **Non**  
 * L'application peut-elle être utilisée par plusieurs utilisateurs ?  **Non**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/blogotext%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/blogotext/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/blogotext%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/blogotext/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations à ajouter sur cette application

## Links

 * Signaler un bug : https://github.com/YunoHost-Apps/BlogoText_ynh/issues
 * Site de l'application : https://blogotext.org/
 * Dépôt de l'application principale : https://github.com/BlogoText/blogotext
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing --debug
ou
sudo yunohost app upgrade blogotext -u https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing --debug
```
