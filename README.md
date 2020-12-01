# README

# Contents
- Introduction
- Prerequisites
- Installing and configuring the module
- License

# Introduction

This Woo-Commerce module provides an easy method to integrate with the payment gateway.
 - The woocommerce-latest directory contains the files that need to be uploaded to the wp-content/plugins/ directory

# Prerequisites

- The module requires the following prerequisites to be met in order to function correctly:
    - Woo-commerce Wordpress extension v3.2+
    - The 'bcmath' php extension module: https://www.php.net/manual/en/book.bc.php
    - SSL **NB: HTTPS is expected to be in place as the payment gateway will respond over SSL when redirecting the user's browser. Failure to provide an environment where HTTPS traffic is possible, will result in the 3DSv2 payment flow failing***

> Please note that we can only offer support for the Module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarentee normal functionality if unsupported changes are made.

# Installing and configuring the module

1. Unzip and upload the plugin folder to your /wp-content/plugins/ directory
2. Activate the plugin through the Plugins menu in WordPress
3. Go to WooCommerce -> Plugins -> Payment-Network and click on the settings button.
4. Enter your MerchantID / Secretkey and update the customer/country code.
5. Set the Enabled option to true.
6. Click 'Save Changes'.

License
----
MIT