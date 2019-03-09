# BlogoText pour YunoHost

![blogotext_logo](sources/images/blogotext_logo.png)


[![Integration level](https://dash.yunohost.org/integration/BlogoText.svg)](https://dash.yunohost.org/appci/app/BlogoText)  
[![Install BlogoText with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=BlogoText)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer BlogoText rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Ceci est BlogoText, un moteur de blog léger.

**Version incluse:** 3.7.6

## Captures d'écran

![blogotext_preview](sources/images/blogotext_preview.png)

## Démo

* [Démo officielle](https://blogotext.org/blog/)

## Configuration

Comment configurer cette application: via le panneau d'administration `https://domain.tld/admin`.

## Documentation

 * Documentation officielle: https://github.com/BlogoText/blogotext/wiki
 * Documentation YunoHost: https://yunohost.org/#/app_blogotext

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

L'authentification LDAP et HTTP est-elle prise en charge? non  
L'application peut-elle être utilisée par plusieurs utilisateurs?  non

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/BlogoText%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/BlogoText/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/BlogoText%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/BlogoText/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/BlogoText%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/BlogoText/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations à ajouter sur cette application

**Plus d'informations sur la page de documentation:**  
https://yunohost.org/packaging_apps

## Links

 * Signaler un bug: https://github.com/YunoHost-Apps/BlogoText_ynh/issues
 * Site de l'application: https://blogotext.org/
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing --debug
ou
sudo yunohost app upgrade BlogoText -u https://github.com/YunoHost-Apps/BlogoText_ynh/tree/testing --debug
```
