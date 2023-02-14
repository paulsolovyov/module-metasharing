# PaulSolovyov MetaSharing

    ``paulsolovyov/module-metasharing``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities
Twitter and Facebook sharing meta tags for Magento 2

![image](https://user-images.githubusercontent.com/108321336/218646463-a39fd35c-578f-42f0-a5ba-370073641c2b.png)


## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/PaulSolovyov`
 - Enable the module by running `php bin/magento module:enable PaulSolovyov_MetaSharing`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Compile the code `php bin/magento setup:di:compile`\*
 - Generate theme files `php bin/magento setup:static-content:deploy`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require paulsolovyov/module-metasharing`
 - enable the module by running `php bin/magento module:enable PaulSolovyov_MetaSharing`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`
