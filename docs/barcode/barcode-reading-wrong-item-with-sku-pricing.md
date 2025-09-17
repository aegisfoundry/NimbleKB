## Symptom
A store uses SKU pricing / Price-in-barcode and some items are not scanning correctly. Scanning an item may result in the wrong item being added to the order.

## Troubleshooting

1) Ensure that the item has the correct barcode. SKU priced item barcodes have a fixed part of the barcode (the first part) and a part that contains pricing and/or check/pad digits.
For example, a SKU priced item may have a barcode of 200377006531, but the fixed part of the barcode is the first six numbers - 200377. If the system is set up with the wrong barcode, such as using the fixed prefix and a random item's pricing part of the barcode, it will not be able to find the item correctly.

2) Ensure that the barcode is not overlapping with another item. Traditionally, SKU priced item barcode prefixes should never overlap with retail barcodes, but if a location has created their own barcode system instead of using an industry standard, they may end up with cases where SKU priced items and non-SKU priced items share the same number space, which can cause issues.
For example, if you have a SKU priced item of 200377 and then create a non-SKU item  200377006531, you are going to get very unpredictable results.
Likewise, if you have two SKU priced items with different fixed barcode lengths that overlap - such as 200377 and 2003778 - you are going to get inconsistent behavior when scanning the barcode.

3) Ensure that all of your SKU priced items are configured to sell by price-in-barcode. This is essentially creating a similar issue to the one above, where you may have inadvertantly created an item that should have been SKU priced, but because it isn't configured that way, can cause the system to read SKU priced items with similar barcode prefixes incorrectly or inconsistently.
