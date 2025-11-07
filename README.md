
# Antom Payment Plugin for Magento 2

[![Packagist Version](https://poser.pugx.org/antom-magento/magento2/v/stable)](https://packagist.org/packages/antom-magento/magento2)  
[![License](https://poser.pugx.org/antom-magento/magento2/license)](https://packagist.org/packages/antom-magento/magento2)

Easily integrate Antom’s payment gateway into your Magento 2 webshop via this free plugin.

---


## 1. Introduction  
This extension enables merchants using Magento 2 (including Adobe Commerce) to offer Antom’s global payment solutions (e.g. AlipayCN, Card etc.).  
It handles secure payment processing, notifications, and automatic order status updates.

---

## 2. Features  
- Turnkey integration with Magento 2 checkout  
- Support for multiple Ant Intl payment methods  
- Automatic order status update via webhook/callback  
- Sandbox and Production modes supported  
- Fully tested for Magento 2.4+ and PHP 7.4 / 8.0+  

---

## 3. Prerequisites  
- Magento: 2.4.2 or higher  
- PHP: ^7.4 or ^8.0  
- Composer: 2.x  

---

## 4. Installation  

### Via Composer (recommended)
From your Magento root directory run:

```
composer require antom-magento/magento2
```
To enable all Antom modules
```
php bin/magento module:enable Antom_Core Antom_Frontend Antom_Adminhtml
```
Run the following commands:
```
php bin/magento setup:upgrade
php bin/magento cache:flush
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```
## 5. Support
Contact us: tech.support.na@service.alipay.com