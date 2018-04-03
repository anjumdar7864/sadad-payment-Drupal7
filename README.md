# Commerce PayFort

## Introduction

**Commerce PayFort** is [Drupal Commerce](https://drupal.org/project/commerce)
module that integrates the [PayFort](http://payfort.com) payement
gateway into your Drupal Commerce shop.

## Basic Installation

 # On PayFort account:

1. Go to security settings and configure settings.

2. Go to technical settings then press redirection.

3. On redirection page:
   - Choose 'yes' for Send Response Parameters.
   - Add Direct Transaction Feedback link as:
      http://YOURSITE/commerce_payfort/response
   - Add Redirection URL as:
      http://YOURSITE/commerce_payfort/redirect

4. Done.

 # On Drupal commerce site:

 1. Download and enable the module from:
      https://www.drupal.org/sandbox/anas_maw/2797129

 2. Configure the payment rule (the `edit` link) with your credentials.   

 3. Done.

## Contact details
Anas Mawlawi
anas.mawlawi89@gmail.com
