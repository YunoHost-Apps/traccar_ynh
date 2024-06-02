<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Traccar pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/traccar.svg)](https://dash.yunohost.org/appci/app/traccar) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/traccar.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/traccar.maintain.svg)

[![Installer Traccar avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traccar)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Traccar rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Traccar est un système de suivi GPS open source. Il prend en charge plus de 200 protocoles GPS et plus de 2 000 modèles de dispositifs de suivi GPS.

### Caractéristiques

- Suivi GPS en temps réel
- Surveillance du comportement des conducteurs
- Rapports détaillés et synthétiques
- Fonctionnalité de géolocalisation
- Alarmes et notifications
- Gestion des comptes et des appareils
- Assistance par e-mail et SMS


**Version incluse :** 6.2~ynh1

**Démo :** <https://www.traccar.org/demo-server/>

## Captures d’écran

![Capture d’écran de Traccar](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.traccar.org/>
- Documentation officielle de l’admin : <https://www.traccar.org/documentation/>
- Dépôt de code officiel de l’app : <https://github.com/traccar/traccar>
- YunoHost Store : <https://apps.yunohost.org/app/traccar>
- Signaler un bug : <https://github.com/YunoHost-Apps/traccar_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/traccar_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
ou
sudo yunohost app upgrade traccar -u https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
