# CertificateCron

This is fork of an OpenSource project created by fluxlabs ag, CH-Burgdorf (https://fluxlabs.ch)

## Requirements
* ILIAS 8
* PHP 7.0 - 7.4

## Installation
First install and enable [Certificate](https://github.com/DEEP-eAcademy/Certificate).

Start at your ILIAS root directory
```bash
mkdir -p Customizing/global/plugins/Services/Cron/CronHook
cd Customizing/global/plugins/Services/Cron/CronHook
git clone https://github.com/DEEP-eAcademy/CertificateCron.git CertificateCron
```
Update and activate the plugin in the ILIAS Plugin Administration
```
cd <ILIAS_ROOT_PATH>
composer install --no-dev
```
