# Pay-Pal-PHP-integration-by-ganesh-kavhar-
E-commerce app paypal integration

PayPal is a payment processing system, We can integrate PayPal with websites by using with php.

PayPal integration file system
PayPal integration file system included 4 files as shown below.

constants.php − This file has included API user name, password and signature.

CallerService.php − This file has included PayPal Services, which is used to call PayPal services.

confirmation.php − This file has included a form with minimum fields required to make payment process and it will return payment success or failure.

PayPal_entry.php − This page has used to send the user the data to PayPal. It acts as an adapter between PayPal and user form.

The user has to download a PayPal SDK file from here and exact a zip file. The zip file contains four php files, We don't need to change any file except constants.php

The constants.php file contains code as shown below −

<?php
   define('API_USERNAME', 'YOUR USER NAME HERE');
   define('API_PASSWORD', 'YOUR PASSWORD HERE');
   define('API_SIGNATURE', 'YOUR API SIGNATURE HERE');
   define('API_ENDPOINT', 'https://api-3t.paypal.com/nvp');
   define('USE_PROXY',FALSE);
   define('PROXY_HOST', '127.0.0.1');
   define('PROXY_PORT', '808');
   define('PAYPAL_URL', 'https://www.PayPal.com/webscr&cmd=_express-checkout&token=');
   define('VERSION', '53.0');
?>
The user will declare User Name, password and signature in above syntax which are placed in constants.php. This is an experimental example so the last amount will be added to sandbox's account.

![Paypal-Logo-Vector-Free](https://user-images.githubusercontent.com/20369800/56292964-cf4bcd80-6145-11e9-965a-614f503cb698.jpg)
