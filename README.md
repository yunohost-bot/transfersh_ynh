<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Transfer.sh for YunoHost

[![Integration level](https://dash.yunohost.org/integration/transfersh.svg)](https://dash.yunohost.org/appci/app/transfersh) ![Working status](https://ci-apps.yunohost.org/ci/badges/transfersh.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/transfersh.maintain.svg)

[![Install Transfer.sh with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transfersh)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Transfer.sh quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Easy and fast file sharing from the command-line. This code contains the server with everything you need to create your own instance.
Transfer.sh currently supports the s3 (Amazon S3), gdrive (Google Drive), storj (Storj) providers, and local file system (local).

### Features

- Made for use with shell
- Share files with a URL
- Unlimited upload
- Files stored forever
- Encrypt your files
- Preview your files in the browser


**Shipped version:** 1.6.1~ynh1

## Screenshots

![Screenshot of Transfer.sh](./doc/screenshots/transfer.sh-about.jpg)

## Documentation and resources

* Official app website: <https://transfer.sh/>
* Official admin documentation: <https://github.com/dutchcoders/transfer.sh/>
* Upstream app code repository: <https://github.com/dutchcoders/transfer.sh>
* YunoHost Store: <https://apps.yunohost.org/app/transfersh>
* Report a bug: <https://github.com/YunoHost-Apps/transfersh_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
or
sudo yunohost app upgrade transfersh -u https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
