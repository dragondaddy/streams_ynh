<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Streams pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/streams.svg)](https://dash.yunohost.org/appci/app/streams) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/streams.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/streams.maintain.svg)

[![Installer Streams avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=streams)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d’installer Streams rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Le [dépôt streams](https://codeberg.org/streams/streams/) vous permet d'installer des sites web connectés au fediverse, avec des fonctionnalités puissantes et novatrices telles que l'identité décentralisée/nomade, des permissions avancées, et bien plus encore (voir [FEATURES](https://codeberg.org/streams/streams/src/branch/dev/FEATURES_fr.md)).

Vos sites web seront compatibles avec **Mastodon**, **Pleroma**, **Pixelfed**, **Friendica**, **Hubzilla**, **Funkwhale**, **Peertube**, **Plume**, **WriteFreely** et bien d'autres encore.


**Version incluse :** 23.08.11~ynh1

## Captures d’écran

![Capture d’écran de Streams](./doc/screenshots/example.png)

## Documentations et ressources

* Dépôt de code officiel de l’app : <https://codeberg.org/streams/streams>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_streams>
* Signaler un bug : <https://github.com/YunoHost-Apps/streams_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/streams_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/streams_ynh/tree/testing --debug
ou
sudo yunohost app upgrade streams -u https://github.com/YunoHost-Apps/streams_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>