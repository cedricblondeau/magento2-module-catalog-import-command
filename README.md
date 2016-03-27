# magento2-module-catalog-import-command
A console command for importing catalog files.

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

- `--images_path`: (default `pub/media/catalog/product`)
- `--behavior`: (default `append`) possible values: append, add_update, replace, delete

## Inspiration
- https://github.com/magento/magento2-sample-data/tree/develop/app/code/Magento/ConfigurableSampleData
