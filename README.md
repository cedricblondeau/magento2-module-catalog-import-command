# magento2-module-catalog-import-command
Import catalog via console command.

**Work in progress.**

## Install
```bash
composer require cedricblondeau/magento2-module-catalog-import-command
php bin/magento module:enable CedricBlondeau_CatalogImportCommand
php bin/magento setup:upgrade
```

## Usage
```bash
php bin/magento catalog:import [-i|--images_path[="..."]] [-b|--behavior[="..."]] csv_file
```

## Inspiration
- https://github.com/magento/magento2-sample-data/tree/develop/app/code/Magento/ConfigurableSampleData
