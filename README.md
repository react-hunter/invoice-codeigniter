InvoicePlane is a self-hosted open source application for managing your invoices, clients and payments.    
For more information visit __[InvoicePlane.com](https://invoiceplane.com)__ or take a look at the __[demo](https://demo.invoiceplane.com)__

1. Download the [latest version](https://invoiceplane.com/downloads)
2. Extract the package and copy all files to your webserver / webspace.
3. Open `http://your-invoiceplane-domain.com/index.php/setup` and follow the instructions.

#### Remove `index.php` from the URL

1. Make sure that [mod_rewrite](https://go.invoiceplane.com/apachemodrewrite) is enabled on your web server.
2. Remove `index.php` from `$config['index_page'] = 'index.php';` in the file `/application/config/config.php`
3. Rename the `htaccess` file to `.htaccess`

If you want to install InvoicePlane in a subfolder (e.g. `http://your-invoiceplane-domain.com/invoices/`) you have to change the .htaccess file. The instructions can be found within the file.
