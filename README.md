# Plugin paddle-woocommerce-3

Integration of Paddle payment processor with WooCommerce 3.

## Settings

In WooCommerce settings in tab Payments select "Paddle payment gate".
Here you need fill "Paddle Vendor ID" and "Paddle API Key" fields.

For using discount coupons (for example, for test payment with 100% discount)
you need create Product on paddle.com and fill field "Product ID" in 
plugin's settings.
In product's settings on paddle.com you need define Webhook's URL
https://your-site.com/index.php/wc-api/paddle_complete.

If you don't wish to use discounts, you can leave field "Product ID" empty 
and uncheck "Discountable" option.