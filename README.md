# shurjoPay - Prestashop

shurjoPay-Online Payment Gateway for Bangladesh. This Module Work for `Prestashop V 1.7.x`

### Prerequisite

  - TLS V1.0(For Sandbox API)
  - [Sandbox Account](https://www.shurjopay.com.bd/be-a-merchant/ "shurjoPay Sandbox Registration")

### Feature

  - Web API
  - Webhook
  - Auto IPN

### Installation Steps:

Please follow these steps to install the shurjoPay Payment Gateway module.

- Step 1: First Download the File from smukhidev/prestashop.
- Step 2: Unzip `prestashop.zip`.
- Step 3: Only Zip prestashop folder.
- Step 4: Upload `prestashop.zip` file to Prestashop admin panel.
- Step 5: Follow the navigation `IMPROVE >> Modules >> Modules & Services >> SHURJOPAY` (Search for SHURJOPAY).
- Step 6: After successful installation go to SHURJOPAY Configure.
- Step 7: In configuration keep Active Module Yes to active/ No to inactive.
- Step 8: Keep Live Mode Yes if you want to use your Securepay/Live Store id & Password. No for Sandbox/Test Store id & Password.
- Step 9: Set module Title, this will show to checkout page. 
- Step 10: Set your valid Merchant ID, Merchant Password provided from shurjoPay (Mandatory). 
- Step 11: You can set additional information to Details.
- Step 12: `IPN: no need to add IPN URL to merchant panel. It's auto configured.` 

### Addition Information:

* This module allows you to accept secure payments by shurjoPay.
* Initially the order status will change to `Processing in progress`.
* Order Status (Payment Success): Should be `Payment accepted` or `Complete`.
* Order Status (Payment Failed): Should be `Payment error`.
* Order Status (Payment Canceled): Should be `Canceled`.

### Image Reference:

* Follow Step 5
![SHURJOPAY in Prestashop Admin Panel](images/adminpanel.png)

* Follow Step 6
![SHURJOPAY Configure Page](images/configure.png)

* Show In Checkout Page(Step 9)
![Checkout Page](images/checkout.png)


---------------------------------------------------------------------------------

- Author : Nazmus Shahadat
- Team Email: shurjopay@shurjomukhi.com.bd (For any query)
- More info: https://www.shurjopay.com.bd

© 2020 shurjoPay ALL RIGHTS RESERVED
