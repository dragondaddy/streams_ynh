<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Streams for YunoHost

[![Integration level](https://dash.yunohost.org/integration/streams.svg)](https://dash.yunohost.org/appci/app/streams) ![Working status](https://ci-apps.yunohost.org/ci/badges/streams.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/streams.maintain.svg)

[![Install Streams with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=streams)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Streams quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

The [streams repository](https://codeberg.org/streams/streams/) lets you install fediverse-connected websites with powerful and innovative features such as decentralized/nomadic identity, permissions framework, and much more (see [FEATURES](doc/FEATURES.md)).

Your websites will be compatible with **Mastodon**, **Pleroma**, **Pixelfed**, **Friendica**, **Hubzilla**, **Funkwhale**, **Peertube**, **Plume**, **WriteFreely** and many, many more.


**Shipped version:** 23.11.05~ynh3

## Screenshots

![Screenshot of Streams](./doc/screenshots/example.png)

## Documentation and resources

* Upstream app code repository: <https://codeberg.org/streams/streams>
* YunoHost Store: <https://apps.yunohost.org/app/streams>
* Report a bug: <https://github.com/YunoHost-Apps/streams_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/streams_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/streams_ynh/tree/testing --debug
or
sudo yunohost app upgrade streams -u https://github.com/YunoHost-Apps/streams_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
