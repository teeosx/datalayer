## Enhanced ecommerce tracking for Google Analytics
Enhanced ecommerce adds functionality to your Google Analytics reports. It shows when customers add items to their shopping carts, when they started the checkout process, and when they completed a purchase.

### Common pitfalls on DataLayer
* Pricing value must not contain any comma
Example :     ‘1,000.00’ is wrong ‘1000.00’ is correct
* All single quote in the String must be escaped with backslash(\)
Example :    ‘Let’s Celebrate’   is wrong       ‘Let\’s Celebrate’ is correct
* Free Items can be included in datalayer but its price must be zero and its name and sku must be unique
* Website with multiple languages must have only one default language value in datalayer (English is favorable)
* Product Price should be discount value if it’s on sale
