<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Traccar untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/traccar.svg)](https://ci-apps.yunohost.org/ci/apps/traccar/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/traccar.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/traccar.maintain.svg)

[![Pasang Traccar dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traccar)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Traccar secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Traccar is an open source GPS tracking system. It supports more than 200 GPS protocols and more than 2000 models of GPS tracking devices.

### Features

- Real-time GPS tracking
- Driver behaviour monitoring
- Detailed and summary reports
- Geofencing functionality
- Alarms and notifications
- Account and device management
- Email and SMS support


**Versi terkirim:** 6.3~ynh1

**Demo:** <https://www.traccar.org/demo-server/>

## Tangkapan Layar

![Tangkapan Layar pada Traccar](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.traccar.org/>
- Dokumentasi admin resmi: <https://www.traccar.org/documentation/>
- Depot kode aplikasi hulu: <https://github.com/traccar/traccar>
- Gudang YunoHost: <https://apps.yunohost.org/app/traccar>
- Laporkan bug: <https://github.com/YunoHost-Apps/traccar_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/traccar_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
atau
sudo yunohost app upgrade traccar -u https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
