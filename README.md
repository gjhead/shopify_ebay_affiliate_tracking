# shopify_ebay_affiliate_tracking
Ebay Affiliates (Formerly Pepperjam) Tracking Code Implementation for Shopify

This is the Ebay Affiliates tracking code made to work in .liquid so that you can implement it in Shopify.

As of this writing, the documentation from EBAY can be found here:

http://help.pepperjamnetwork.com/advertiser/integration/dynamic

Two items that are not included in this code (which are optional from the documentation) are:

CATEGORY: This cannot be pulled from the item through shopify.

NEW_TO_FILE: Still unable to test for this through Shopify.


This code goes on the Checkout Confiramtion page which Shopify does not allow us to edit, so to add this code you need to go to:

Settings > Online Store > Checkout

Under "Order Processing" this code goes in the "Additional content and scripts" box.
