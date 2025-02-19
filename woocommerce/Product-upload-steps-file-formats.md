# WooCommerce Product Upload Guide

## Introduction
This guide provides a step-by-step approach to uploading different types of products in WooCommerce using an Excel file. It includes product variations, grouped products, external/affiliate products, and discount options.

## Product Types in WooCommerce
WooCommerce supports multiple product types, including:
- **Simple Products**: Single items with no variations.
- **Variable Products**: Products with multiple variations such as color, size, or material.
- **Grouped Products**: A collection of related products sold together.
- **External/Affiliate Products**: Products linked to external websites for purchase.

## WooCommerce Product Upload Fields
Here is the list of important fields used in the WooCommerce product upload process:

| Field Name             | Description |
|------------------------|-------------|
| SKU                   | Unique product identifier |
| Name                  | Product title |
| Description           | Full description of the product |
| Short Description     | A brief description of the product |
| Regular Price         | Original price of the product |
| Sale Price           | Discounted price (if applicable) |
| Stock                | Available inventory count |
| Stock Status         | In stock, out of stock, or backorder |
| Product Type         | Type of product (Simple, Variable, Grouped, External) |
| Parent SKU           | Used for variations, links variations to a main product |
| Attribute Name       | Product attribute (e.g., Color, Size) |
| Attribute Values     | Possible values for attributes |
| External URL         | For affiliate products, links to an external store |
| Categories           | Categories and subcategories (e.g., Apparel > T-Shirts) |
| Tags                 | Keywords for filtering products |
| Images               | URL of product images |
| Weight              | Product weight for shipping calculation |
| Dimensions          | Length, width, and height of the product |
| Shipping Class      | Defines shipping method (e.g., Standard, Heavy) |
| Meta Title          | SEO title for the product page |
| Meta Description    | SEO-friendly description |

## How to Upload WooCommerce Products
### 1. Prepare the Excel File
- Fill out the required fields as per the table above.
- Ensure that variable products have their attributes defined correctly.
- Use external URLs for affiliate products.
- Assign categories and tags appropriately.

### 2. Uploading the File in WooCommerce
1. Navigate to **WooCommerce > Products > Import**.
2. Click **Choose File** and select the Excel file.
3. Click **Continue** and map the columns to WooCommerce fields.
4. Click **Run Importer** and wait for the process to complete.

## Example Product Upload Files
The following downloadable Excel files contain examples of different product types:

- **[WooCommerce Product Upload Template](sandbox:/mnt/data/woocommerce_product_upload.xlsx)**
- **[WooCommerce Product Upload (All Formats)](sandbox:/mnt/data/woocommerce_product_upload_all_formats.xlsx)**
- **[WooCommerce Product Upload (Complete Format)](sandbox:/mnt/data/woocommerce_product_upload_complete.xlsx)**

