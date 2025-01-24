<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Matomo YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/matomo)](https://ci-apps.yunohost.org/ci/apps/matomo/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/matomo)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/matomo)

[![Instalatu Matomo YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matomo)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Matomo YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Matomo is the leading Free/Libre open analytics platform. At the end of the five-minute installation process, you will be given a JavaScript code. Simply copy and paste this tag on websites you wish to track and access your analytics reports in real-time.

Matomo aims to be a Free software alternative to Google Analytics and is already used on more than 1,400,000 websites. Privacy is built-in!


**Paketatutako bertsioa:** 5.2.2~ynh1

**Demoa:** <https://demo.matomo.org>

## Pantaila-argazkiak

![Matomo(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://matomo.org>
- Administratzaileen dokumentazio ofiziala: <https://matomo.org/docs>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/matomo-org/matomo>
- YunoHost Denda: <https://apps.yunohost.org/app/matomo>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/matomo_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/matomo_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
edo
sudo yunohost app upgrade matomo -u https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
