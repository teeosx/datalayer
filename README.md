## Enhanced ecommerce tracking for Google Analytics
Enhanced ecommerce adds functionality to your Google Analytics reports. It shows when customers add items to their shopping carts, when they started the checkout process, and when they completed a purchase.

## Data Layer
The data layer contains information that can be used by Google Tag Manager. This information can be used in tags, triggers, and variables. Google Tag Manager will automatically create a data layer and try to add information. For example, if you enable scroll depth tracking, Google Tag Manager will add details about scroll behavior to the data layer. You can also implement your own custom data layer to pass your own values to Google Tag Manager. The data layer can include static information that is pre-defined when the page loads or the information can be dynamic; this is where information is made available depending on the actions people take after the page has loaded.

### Data Layer warning
* Pricing value must not contain any comma<br/>
 Example : ‘1,000.00’ is wrong ‘1000.00’ is correct
* All single quote in the String must be escaped with backslash('\\') <br/>
 Example : ‘Let’s Celebrate’   is wrong       ‘Let\’s Celebrate’ is correct
* Free Items can be included in datalayer but its price must be zero and its name and sku must be unique
* Website with multiple languages must have only one default language value in datalayer (English is favorable)
* Product Price should be discount value if it’s on sale
