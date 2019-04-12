# AjaxShoppingCartUpdate-Magento2

# Overview

Save For Later extension for Magento 2 has been developed by the product team at RLTSquare. An optimized shopping experience is the key to increase the conversion rates of your store. This extension enables you to display a “Save For Later” option in the Checkout Cart page. When you add the product to the Save For Later, it gets removed from the shopping cart.  This extension allows your customers to save the products they are interested in, so they can place the order later. The items are saved in the “Saved For Later” tab in the Customer Dashboard left side panel which makes it easier to find them again. With the retrieve to cart option, it takes the items directly to the Checkout page. The customers can easily view or remove the products. The customers can avail this feature only after signing up on your store. The admin can also disable the Save For Later option from the store configuration. 

Here are some of the salient features for the extension:

```
1. Allows customers to save the products of their choice.
2. Allows customers to view the saved product on their profile and they can directly view the product information by clicking the Saved For Later tab in Customer dashboard.
3. Works for all kind of products, i.e virtual, simple, configurable, bundle, group and downloadable.
4. Enable/disable the “Save For Later” key for products.
5. When disabled the grid and the Save For Later tab in the customer dashboard vanishes.
6. Visible on Checkout Cart page and customer dashboard.
7. Increase the leads because it encourages the customers to sign up.
```

## Installation

### Magento® Marketplace

This extension will also be available on the Magento® Marketplace when approved.

### Manually

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/save-for-later
   ```

   Wait while composer is updated.
   
   #### OR
   
   You can also download code from this repo under Magento® 2 following directory:
    
    ```
    app/code/RLTSquare/SaveForLater
    ```    

3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_SaveForLater
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

1. This Magento® extension works on Magento 2.2 and 2.3 versions. Tested on versions 2.2.5 and above.

2. Tested on different themes specifically Ultimo, Porto and certain custom themes

For details, read our blog:
https://www.rltsquare.com/blog/save-for-later-magento-2-extension/
