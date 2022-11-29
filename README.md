# Luma Data Pack

This Data Pack is used to approximate the Luma Sample Data installed via multiple modules or by the commerce cli command `bin/magento sampledata:deploy`
Sample Data not included in this version: Orders, Invoices, Credit Memos, Shipments, Gift Registry, Wishlists, Tax Rules and Rates


#### Requirements
Addition of the Data Installer: `composer config repositories.installer git https://github.com/PMET-public/module-data-install.git;composer config repositories.importer git https://github.com/PMET-public/FireGento_FastSimpleImport2.git;composer require magentoese/module-data-install:dev-master` then run `bin/magento setup:upgrade`

To add this package via composer: 
`composer config repositories.luma git https://github.com/PMET-public/vertical-data-luma.git;composer require magentoese/vertical-data-luma:dev-main` No need to run `setup:upgrade`