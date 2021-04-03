# Yellow pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/yellow.svg)](https://dash.yunohost.org/appci/app/yellow) ![](https://ci-apps.yunohost.org/ci/badges/yellow.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/yellow.maintain.svg)  
[![Installer Yellow avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yellow)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Yellow rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Datenstrom Yellow est un CMS (Système de gestion de contenu) conçu pour rendre la création d'un site internet ultra-simple et facile à utiliser. Le jaune ne nécessite pas de base de données.

**Version incluse :** 0.8.17

## Captures d'écran

![](https://datenstrom.se/media/images/datenstrom-yellow-en.png)

## Démo

* [Démo officielle](https://datenstrom.se/yellow/demo/)

## Configuration

* Comment configurer cette application : via le panneau d'administration.

## Documentation

 * Documentation officielle : https://datenstrom.se/yellow/help/
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/yellow.svg)](https://ci-apps.yunohost.org/ci/apps/yellow/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/yellow.svg)](https://ci-apps-arm.yunohost.org/ci/apps/yellow/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/yellow_ynh/issues
 * Site de l'application : https://datenstrom.se/
 * Dépôt de l'application principale : https://github.com/datenstrom/yellow/
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeur

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/yellow_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/yellow_ynh/tree/testing --debug
ou
sudo yunohost app upgrade yellow -u https://github.com/YunoHost-Apps/yellow_ynh/tree/testing --debug
```
