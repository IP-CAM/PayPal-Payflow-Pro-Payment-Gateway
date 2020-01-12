## Upgrade
To upgrade to the latest:
* Same as install, while overwriting existing files.
* Consider clearing Error Log (System > Error Log) when logged in as Admin.

## Installation
To install:
* Extract the ZIP file.
* Copy the files to your server to the appropriate directories.
* Log as admin and go to Extensions > Payments.  (If 'PayPal PayFlow Pro' isn't in this list, the files may not be uploaded correct or have the correct permissions.)
* Click 'Install' on 'PayPal PayFlow Pro'.
* Click 'Edit' on 'PayPal PayFlow Pro'.
* Enter PayFlow Pro login information (Remember to change the status to 'Enabled').
* Click 'Save'.

Use the Test server first.  Then switch to the Live server when everything is working. When switching to Live server, after having done testing in Test mode, remember to clear Error Log (System > Error Log) when logged in as Admin.

## PayFlow Pro Comment1 & Comment2 Template Variables:
{id} - opencart order table id
{ip} - ip address of client's web browser
{total_models} - sum total of unique products
{total_products} - sum total of all product quantities
{cart} - summary of cart with quantity and model # i.e. 1xProduct 1, 3xProduct 2

## Creating a PayFlow Pro User Account for Opencart Orders
In the OpenCart admin back end of this plugin the PayFlow Pro User field is required. If you already have another PayFlow Pro User Account besides the main PayFlow Pro Merchant login feel free to use that.
To create a another user account, login to your PayFlow Pro Merchant account at [manager.paypal.com](https://manager.paypal.com/) to create another user account specifically for your opencart website orders. 
