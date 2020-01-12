# PayPal Payflow Pro Payment Gateway
**NOTE:** Currently not compatible with Opencart 2, and currently no plans to become compatible. Opencart 2 comes with a free payflow pro payment plugin. I haven't used it. Perhaps it may suffice for your opencart 2 needs.

## Overview
---
Easily process credit cards in OpenCart via your PayPal PayFlow Pro account ([manager.paypal.com](manager.paypal.com)). On checkout users enter credit card number, expiration date and cvv code (see images). Benefit from PayPal Fraud Protection Services as the needed information is transmitted for each transaction (all Fraud Protection Services must still be completely administered in the PayPal Manager). Start processing credit cards in OpenCart now.

## Features
---
1. Like other OpenCart payment modules you can specify 'Order Status', 'Total', and 'Geo Zone' (see images).
2. Options to specify Comment 1 and Comment 2 for every PayFlow Pro transaction including optional template variables {id}, {ip}, {total_models}, {total_products}, and {cart} (see Documentation and Images tabs).
3. Receive an email:
* when a transaction is being held in review by PayFlow Pro Fraud Protection Service to be reviewed by you. The default PayFlow Pro Fraud Protection Service filter action is review (manager.paypal.com > Service Settings > Fraud Protection > Edit Standard Filters - after making changes click "Deploy" - allow at least 1 hour to take effect).
* when the plugin is misconfigured and not able to connect properly to the gateway
4. Events logged to the backend (System -> Error Logs) include:
* When unable to send to or receive from PayPal Payflow Pro servers
* When unable to authenticate with PayPal Payflow Pro servers
* When in test mode, the parameter string sent to the paypal servers (with sensitive data removed)
5. Specify different order statuses for order success, FPS review and credit card processor timeout (see Admin options in images)

## Terms
---
Allowed use is for one OpenCart site only. Use without SSL is not permitted. No guarantees.

## Note
---
* Ensure that your website has an SSL certificate before using this extension live.
* Requires a PayPal Payflow Pro sub-user account login ([manager.paypal.com](manager.paypal.com)) because use of the main/administrative PayFlow Pro account login is not allow for security reasons. See Documentation tab for further details.
* Realize Paypal Payflow Pro is available only in USA and Australia ([https://developer.paypal.com/webapps/developer/docs/classic/howto_product_matrix/](https://developer.paypal.com/webapps/developer/docs/classic/howto_product_matrix/))!
