# Miniflux pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/miniflux.svg)](https://dash.yunohost.org/appci/app/miniflux) ![](https://ci-apps.yunohost.org/ci/badges/miniflux.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/miniflux.maintain.svg)  
[![Installer Miniflux avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=miniflux)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Miniflux rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/install) pour apprendre comment l'installer.*

## Vue d'ensemble

Miniflux est un agrégateur de flux RSS minimaliste.

**Version incluse :** 2.0.30

## Captures d'écran

![](https://miniflux.app/images/overview.png)

## Configuration

La plupart des éléments peuvent être modifiés à la volée dans Web-UI dans la page de configuration.

Vous pouvez configurer Simple Torrent en modifiant le fichier `/etc/miniflux.conf` en vous aidant de la [documentation](https://miniflux.app/docs/configuration.html).

## Documentation

 * Documentation officielle : https://miniflux.app/docs/index.html

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Non**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/miniflux.svg)](https://ci-apps.yunohost.org/ci/apps/miniflux/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/miniflux.svg)](https://ci-apps-arm.yunohost.org/ci/apps/miniflux/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/miniflux_ynh/issues
 * Dépôt de l'application principale : https://github.com/miniflux/v2
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/miniflux_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/miniflux_ynh/tree/testing --debug
ou
sudo yunohost app upgrade miniflux -u https://github.com/YunoHost-Apps/miniflux/tree/testing --debug
```
