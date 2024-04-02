<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Matomo pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/matomo.svg)](https://dash.yunohost.org/appci/app/matomo) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/matomo.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/matomo.maintain.svg)

[![Installer Matomo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matomo)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Matomo rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Matomo est la principale plateforme d'analyse ouverte Free/Libre. À la fin du processus d'installation de cinq minutes, vous recevrez un code JavaScript. Copiez et collez simplement cette balise sur les sites Web que vous souhaitez suivre et accédez à vos rapports d'analyse en temps réel.

Matomo se veut une alternative logicielle gratuite à Google Analytics et est déjà utilisé sur plus de 1 400 000 sites Web. La confidentialité est intégrée !

**Version incluse :** 5.0.3~ynh1

**Démo :** <https://demo.matomo.org>

## Captures d’écran

![Capture d’écran de Matomo](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://matomo.org>
- Documentation officielle de l’admin : <https://matomo.org/docs>
- Dépôt de code officiel de l’app : <https://github.com/matomo-org/matomo>
- YunoHost Store : <https://apps.yunohost.org/app/matomo>
- Signaler un bug : <https://github.com/YunoHost-Apps/matomo_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/matomo_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade matomo -u https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
