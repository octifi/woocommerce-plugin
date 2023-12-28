=== lattiudepay  Mobile Payment System for WooCommerce ===
Contributors: LatitudePay
Tags: lattiudepay  payments, woocommerce, payment gateway, installments
Requires at least: 5.7.2
Tested up to: 5.7.2
Stable tag: 2.1.2
Requires PHP: 5.5
License: MIT

Allows payments with lattiudepay Payment on your WooCommerce website

== Installation ==

= Using The WordPress Dashboard =

1. Navigate to the 'Add New' in the plugins dashboard
2. Search for 'lattiudepay Payment'
3. Click 'Install Now'
4. Activate the plugin on the Plugin dashboard

= Uploading in WordPress Dashboard =

1. Navigate to the 'Add New' in the plugins dashboard
2. Navigate to the 'Upload' area
3. Select `woocommerce-octifi.zip` from your computer
4. Click 'Install Now'
5. Activate the plugin in the Plugin dashboard

= Using FTP =

1. Download `woocommerce-octifi.zip`
2. Extract the `woocommerce-octifi` directory to your computer
3. Upload the `woocommerce-cryptapi` directory to the `/wp-content/plugins/` directory
4. Activate the plugin in the Plugin dashboard


== Changelog ==

= 1.0 =
* Initial release.

== Upgrade Notice ==
= 1.0.2 =
- Country code added to checkout web redirect

= 1.0.3 =
- Saving Checkout token in the order

= 1.0.4 =
- Modal popup option added

= 1.0.5 =
- SDK URL Changed

= 1.0.6 =
- Plugin setting payment type option changed to radio button and changed the labels too.
- Setting the order status as processing for the successful payment instead of completed status.

= 2.0.1 =
- Payment actions(authorize and capture) select option provided.
- If payment option authorize selected, capture will be carried out when order status changed to complete.
- Id payment option capture selected, both authorize and capture will be carried out during the checkout.

= 2.0.2 =
- Bug fixed while displaying error message from payment gateway.

= 2.0.3 =
- Added new feature, now captured status will display in the admin order page and if not captured, admin capture manually.

= 2.0.4 =
- Bug Fixed on automatic capture on order completion

= 2.0.5 =
- Bug Fixed on checkout script rendering, added slashes to the string params

= 2.0.6 =
- Bug Fixed on listing image output
- Bug Fixed on listing price output
- Plugin meta data updated
- TOS links updated

= 2.0.7 =
- changed prfixes
- changed CURL to HHTP API
- changed JS and CSS integration structure


= 2.0.8 =
- changed prfixes
- added sanitization

= 2.0.9 =
- moved shop listing message below price
- removed js console logs
- fixed checkout logo size

= 2.0.10 =
- removed modal pop up functionality
- min summ functionality created
- added option to hide text in archives

= 2.0.11 =
- fixed single product output issue
- changed single product hooks
- fixed JS model layers issue

= 2.1.0 =
- sandbox and live add 
- Home page text, home page text enable disable show add
- Minimum sum bug fix
- security upgrade
- design issue fix
- Added latitudepay logo
- Renamed octifi to latitudepay

= 2.1.1 = 
- live mode bug fix 
- code structure change 
- cancel payment problem solve 
- env file changes

= 2.1.2 =
- Test mode alert added
- css change

= 2.1.3 =
- Learn more - T&C link to change
- Learn more - "We accept all the major bank debit cards"
- Reduce the radius of the Learn more pop up
- Select country field added at admin side - Select the country dropdown
- Based on selected country - use the respective env variables

= 2.1.4 =
- Will replace Be the savvy customer and choose LatitudePay at checkout with Make Every Purchase Affordable
- Pay only 1/3 today  -> Split your payment into 3 affordable instalments. Always 0% interest and no hidden fees.
- Use both debit or credit card -> No credit card? No Problem! We accept any Singapore/malaysia bank issued debit cards
- Will remove the 'Earn 1.5% cashback'   column completely.
- Updating the t&c link for appropriate country

= 2.1.6 =
- fixed the broken setting link from the plugin section.
- changed the base url from "https://k2.octifi.me" to "https://k2.latitudepay.me
- every where we update the domain to sg.latitudepay.com

= 2.1.7 =
- changed the version number to 2.1.7
- bucket domain updated for prod
- after failed the order, when we click on pay button the payment is visible.

= 2.1.8 =
- changed the version number to 2.1.8
- Authorise option and payment redirection to WP code compatibility with Woocommerce V8.4 got fixed.
