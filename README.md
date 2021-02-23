# README

# Contents

- Introduction
- Prerequisites
- Installing the payment module
- License

# Introduction

This Woo-Commerce module provides an easy method to integrate with the payment gateway.
 - The woocommerce-latest directory contains the files that need to be uploaded to the wp-content/plugins/ directory
 - Supports WooCommerce versions: **3.2 - 4.7**
 - Supports Recurring payments using WooCommerce subscriptions plugin found here: https://woocommerce.com/products/woocommerce-subscriptions/?utm_source=google&utm_medium=search&utm_campaign=marketplace_search_brand_row&utm_content=+woocommerce_+subscriptions&gclid=CjwKCAiA9bmABhBbEiwASb35V6LBxRec_Gx8zRBjbVNg_iDUE91R4I1wlS0Sd7RjZ--DbOBW_sNIRBoCflkQAvD_BwE#

# Prerequisites

- The module requires the following prerequisites to be met in order to function correctly:
    - Woo-commerce Wordpress extension
    - The 'bcmath' php extension module: https://www.php.net/manual/en/book.bc.php

> Please note that we can only offer support for the Module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarantee normal functionality if unsupported changes are made.

# Installing and configuring the module

1. Unzip and upload the plugin folder to your /wp-content/plugins/ directory or navigate to Plugins -> add new plugin -> upload plugin and then drop the zip file where specified
2. Activate the plugin through the Plugins menu in WordPress
3. Go to WooCommerce -> Plugins -> Payment-Network and click on the settings button
4. Enter your MerchantID / Secretkey and update the customer/country code
5. If you own a custom form on your gateway, enter the full URL to it in the custom form box (Including trailing /)
6. Selects what type of integration you would like to use
7. Set the Enabled option to true
8. Click 'Save Changes'

License
----
MIT
