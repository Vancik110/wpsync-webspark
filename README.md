# wpsync-webspark
Product synchronization plugin via API.

To install the plugin, use the standard WordPress installation interface, or place the contents of the archive in the wp-content/plugins/ folder.
After activating the plugin, a cron job will be launched to import products to your site from https://my.api.mockaroo.com/products.json?key=89b23a40
From now on, it will run every hour. After deactivating the plugin, the cron job will be deleted.
