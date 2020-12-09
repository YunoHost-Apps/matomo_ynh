# Matomo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/matomo.svg)](https://dash.yunohost.org/appci/app/matomo) ![](https://ci-apps.yunohost.org/ci/badges/matomo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matomo.maintain.svg)  
[![Install Matomo with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=matomo)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Matomo quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Matomo is the leading Free/Libre open analytics platform. It is a full-featured PHP MySQL software program that you download and install on your own webserver. At the end of the five-minute installation process, you will be given a JavaScript code. Simply copy and paste this tag on websites you wish to track and access your analytics reports in real-time.

**Shipped version:** 4.0.5

## Screenshots

![](https://img.matomo.org/spai/w_660+q_lossless+ret_img+to_webp/https://static.matomo.org/wp-content/uploads/2019/03/matomo-analytics-dashboard.png)

## Demo

* [Official demo](https://demo.matomo.org)

## Configuration

1. The app will require to complete the registration process after the instllation is complete by **visiting the domain** on  which Matomo is installed.
1. The MySQL database credentials will be sent to the **admin mail**. Fill these details while doing the registration process.
1. No LDAP support yet for the app.

## Documentation

 * Official documentation: https://matomo.org/docs
 * YunoHost documentation: https://yunohost.org/#/app_matomo

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/matomo%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/matomo/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/matomo%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/matomo/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/matomo_ynh/issues
 * App website: https://matomo.org/
 * Upstream app repository: https://github.com/matomo-org/matomo
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/matomo_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
or
sudo yunohost app upgrade matomo -u https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
```
