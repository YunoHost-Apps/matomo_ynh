# Matomo pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/matomo.svg)](https://dash.yunohost.org/appci/app/matomo) ![](https://ci-apps.yunohost.org/ci/badges/matomo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matomo.maintain.svg)  
[![Installer Matomo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=matomo)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Matomo rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Matomo est une plateforme d'analyse open source de mesure de statistiques Web. Il s'agit d'un logiciel PHP MySQL complet que vous téléchargez et installez sur votre propre serveur Web. À la fin du processus d'installation de cinq minutes, vous recevrez un code JavaScript. Copiez et collez simplement cette balise sur les sites Web que vous souhaitez suivre et accédez à vos rapports d'analyse en temps réel.

**Version incluse :** 4.0.5

## Captures d'écran

![](https://img.matomo.org/spai/w_660+q_lossless+ret_img+to_webp/https://static.matomo.org/wp-content/uploads/2019/03/matomo-analytics-dashboard.png)

## Démo

* [Démo officielle](https://demo.matomo.org)

## Configuration

1. Une fois l'installation terminée, l'application devra terminer le processus d'enregistrement en **visitant le domaine** sur lequel Matomo est installé.
1. Les informations d'identification de la base de données MySQL seront envoyées à **l'email admin**. Remplissez ces détails lors du processus d'inscription.
1. Le support LDAP n'est pas encore implémenté pour cette l'application.

## Documentation

 * Documentation officielle : https://matomo.org/docs
 * Documentation YunoHost : https://yunohost.org/#/app_matomo_fr

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/matomo%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/matomo/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/matomo%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/matomo/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/matomo_ynh/issues
 * Site de l'application : https://matomo.org/
 * Dépôt de l'application principale : https://github.com/matomo-org/matomo
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/matomo_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade matomo -u https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
```
