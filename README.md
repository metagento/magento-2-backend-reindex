# Magento 2 Backend Reindex by Metagento

By default in Magento 2, Admins have to use command line to reindex, there is no way to do that in backend like Magento 1.

This extension solves the problem, Admins will be able to reindex in Index Management page.


![Backend Reindex for Magento 2 by Metagento](http://www.metagento.com/media/metagento/backendreindex-m2/index-management.jpg)

Install using composer

```
composer require metagento/backend-reindex-magento2:*
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Any question, please visit https://www.metagento.com/
