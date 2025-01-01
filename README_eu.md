<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Traccar YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/traccar)](https://ci-apps.yunohost.org/ci/apps/traccar/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/traccar)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/traccar)

[![Instalatu Traccar YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traccar)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Traccar YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Traccar is an open source GPS tracking system. It supports more than 200 GPS protocols and more than 2000 models of GPS tracking devices.

### Features

- Real-time GPS tracking
- Driver behaviour monitoring
- Detailed and summary reports
- Geofencing functionality
- Alarms and notifications
- Account and device management
- Email and SMS support


**Paketatutako bertsioa:** 6.5~ynh1

**Demoa:** <https://www.traccar.org/demo-server/>

## Pantaila-argazkiak

![Traccar(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.traccar.org/>
- Administratzaileen dokumentazio ofiziala: <https://www.traccar.org/documentation/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/traccar/traccar>
- YunoHost Denda: <https://apps.yunohost.org/app/traccar>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/traccar_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/traccar_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
edo
sudo yunohost app upgrade traccar -u https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
