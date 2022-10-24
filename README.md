##### slack-data-connector

# Product Description & Purpose

Sync your Shopify product catalog to Yext. Shopify is a complete e-commerce platform that allows businesses to create and customize their own online storefront to sell products. Through Shopify, businesses can manage products, inventory, payments, and shipping.

The Shopify V2 Data Connectors pulls product data such as products, variants, and images from your Shopify product catalog into Yext to power rich customer experiences with Yext Search and Pages. This app keeps your product catalog up to date in near real time, any changes made to your product data in Shopify will sync automatically to the Yext Knowledge Graph — without manual oversight.


This app creates the following custom connectors:	

- shopify\_ParentProducts
- shopify\_VariantProucts
- shopify\_VariantImages
- shopify\_ParentProductUpdates
- shopify\_VariantProductUpdates
- shopify\_ProductDeletions

This app uses the built-in Product entity type and adds the following custom Shopify fields to the entity type:	

- shopify\_compareAtPrice
- shopify\_option1
- shopify\_option2
- shopify\_option3
- shopify\_parentProduct
- shopify\_productCategory
- shopify\_productType
- shopify\_shopifyInventoryItemID
- shopify\_shopifyInventoryPolicy
- shopify\_shopifyProductRole
- shopify\_taxableItem
- shopify\_variants
- shopify\_deletedInShopify


# Requirements

To use this app you will need to have the following before you install:

- Your Shopify store name
- Have created a custom app in Shopify with the proper API permissions
- Generated and have access to your Shopify API Access Token

Follow the step-by-step instructions below to install the Shopify v2 Products Connectors app.

# How to Install

If you are an existing Yext customer, you can install the  Shopify v2 Products Connectors here <https://www.yext.com/s/me/apps/94796>

If you are currently using a Yext sandbox account, you can install the Shopify v2 Products Connectors here <https://sandbox.yext.com/s/me/apps/166633>.

If you are not an existing customer, but interested in learning more, try out a free trial here for a production account, or sign up for Hitchhikers and get started with a sandbox account, here <https://hitchhikers.yext.com/>. 

Install the connector to begin pulling in your Shopify data into your Knowledge Graph! 


### To install the Shopify v2 Products Connectors:

1. Click the Install button.
2. Enter your Shopify details, your Shopify store name (e.g. https://[YOURSTORENAME].myshopify.com/) and provide your API Access Token
3. Authorize the changes to your account and click Submit.

Once the app is installed you will be directed to the Connectors page where you will manually run 3 connectors.
4. First, run the Parent Products connector, this is the page that you are automatically redirected to.
5. Then, navigate to the other connectors installed with this app. Run the Variant Products Connector and finally the Variant Images Connector.

Once you have manually run all 3 connectors you are finished! Each connector will run comprehensively once per day and other products will stay up to date near-real time. 
##### \*Please note: Variant images will NOT be updated near-real time and will only be updated during the daily comprehensive pull.






