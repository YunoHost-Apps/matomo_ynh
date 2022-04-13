# Matomo pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/matomo.svg)](https://dash.yunohost.org/appci/app/matomo) ![](https://ci-apps.yunohost.org/ci/badges/matomo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matomo.maintain.svg)  
[![Installer Matomo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matomo)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Matomo rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Plateforme d'analyse open source de mesure de statistiques Web

**Version incluse :** 4.9.0~ynh1

**Démo :** https://demo.matomo.org

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

1. Une fois l'installation terminée, l'application devra terminer le processus d'enregistrement en **visitant le domaine** sur lequel Matomo est installé.
1. Les informations d'identification de la base de données MySQL seront envoyées à **l'email admin**. Remplissez ces détails lors du processus d'inscription.
1. Le support LDAP n'est pas encore implémenté pour cette l'application.

## Documentations et ressources

* Site officiel de l'app : https://matomo.org
* Documentation officielle de l'admin : https://matomo.org/docs
* Dépôt de code officiel de l'app : https://github.com/matomo-org/matomo
* Documentation YunoHost pour cette app : https://yunohost.org/app_matomo
* Signaler un bug : https://github.com/YunoHost-Apps/matomo_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/matomo_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade matomo -u https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps