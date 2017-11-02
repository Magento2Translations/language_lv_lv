# Latvian (latviešu) Magento2 Language Pack (lv_LV)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Latvian (latviešu) translations used can be found [here](https://crowdin.com/project/magento-2/lv).
This translation is usefull for people living in the Latvia (Latvija).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [2.0.2](https://crowdin.com/project/magento-2/lv#/2.0.2) at Crowdin and based on the Magento 2.0.2 sourcefiles.
There have been  3626 strings translated of the 7776 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/47)

# Installation
**Please select the git branch appropriate for your magento version from this repo.**
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_lv_lv:2.0.2.x-dev
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_lv_lv/archive/2.0.2.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_lv_lv`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/lv_LV/lv_LV.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Latvian (Latvia)*'

# Contribute
To help push the '*Latvian (latviešu) Magento2 Language Pack (lv_LV)*' forward please goto [this](https://crowdin.com/project/magento-2/lv) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).