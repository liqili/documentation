:show-content:

========
Products
========

**Odoo eCommerce** allows you to :ref:`add products <ecommerce-products-add-products>` and manage
your :ref:`product pages <ecommerce-products-product-page>` directly within the Website app. You can
also add :ref:`product variants <ecommerce-products-product-variants>` and
:ref:`digital files <ecommerce-products-digital-files>`,
:ref:`translate <ecommerce-products-translation>` your product page content,
:ref:`manage your stock <ecommerce-products-stock-management>`, and enable
:ref:`product comparisons <ecommerce-products-product-comparison>`.

.. _ecommerce-products-add-products:

Add products
============

.. _ecommerce-products-create-products:

Create products
---------------

To create a product from the frontend, click :guilabel:`+ New` in the top-right corner, then
:guilabel:`Product`. Enter the :guilabel:`Product Name`, :guilabel:`Sales Price`, the default
:guilabel:`Customer Taxes` for local transactions, and :guilabel:`Save`. You can then update the
product's details, add an image, and :ref:`customize <ecommerce-products-customization>` the product
page. When you :guilabel:`Save`, the product page is automatically published.

.. tip::
   - You can also create a product from the backend by going to
     :menuselection:`Website --> eCommerce --> Products` and clicking :guilabel:`New`.
   - Products created from the frontend are automatically :ref:`published <website/un-publish-page>`,
     while products created from the backend are not. To publish a product, click the
     :guilabel:`Go to Website` smart button to access the product page, then toggle the switch from
     :guilabel:`Unpublished` to :guilabel:`Published`.

.. _ecommerce-products-import-products:

Import products
---------------

To :ref:`import product data <import-data>` using XLSX or CSV files, go to
:menuselection:`Website --> eCommerce --> Products`, click the :icon:`fa-cog` (:guilabel:`gear`)
icon, then :ref:`Import records <import-data>`.

.. tip::
   To publish **large batches** of products, follow these steps:

   #. Go to :menuselection:`Website --> eCommerce --> Products`;
   #. Remove the :guilabel:`Published` filter;
   #. Select the :guilabel:`List` view;
   #. Click the :icon:`fa-sliders` (:guilabel:`dropdown toggle`) icon and enable
      :guilabel:`Is published`;
   #. Click the :guilabel:`Is Published` column to re-order it by **published** or **unpublished**
      products;
   #. Select the products to publish by ticking their box;
   #. Tick any box of the selected products in the :guilabel:`Is Published` column to publish them
      all.

Shop page
=========

To customize the layout of your main :guilabel:`Shop` page or modify its content, click
:guilabel:`Edit`. Go to the :guilabel:`Blocks` tab to add
:doc:`building blocks <../../websites/website/web_design/building_blocks>` or to the
:guilabel:`Customize` tab to change the page layout or add features:

- :guilabel:`Layout`: select :guilabel:`Grid` or :guilabel:`List`.

   - :guilabel:`Size`: set the number of products displayed per page;
   - :guilabel:`Style`: select :guilabel:`Default`, :guilabel:`Cards`, :guilabel:`Thumbnails`, or
     :guilabel:`Grid`;
   - :guilabel:`Image Size`: choose the aspect ratio for your product images:
     :guilabel:`Landscape (4/3)`, :guilabel:`Default (1/1)`, :guilabel:`Portrait (4/5)`, or
     :guilabel:`Vertical (2/3)`. You can also adjust the display by changing the :guilabel:`Fill`
     options to best fit your design preferences.

- :guilabel:`Search Bar`: toggle the switch to enable the search bar to help customers quickly find
   specific products.

- :guilabel:`Prod. Desc.`: toggle the switch to display the product description below the product's
  name.

- :guilabel:`Categories`: select :guilabel:`Left` to display the product categories on the left side
  of the products page, and/or choose :guilabel:`Top` to display them at the top of the page.

  - :guilabel:`Collapse Categories`: toggle the switch to group products in the same category.

- :guilabel:`Datepicker`: toggle the switch to display a date range calendar to check the
   availability of rental products over a specific period. The :guilabel:`Rental` app must be
   installed to use this feature.

- :guilabel:`Attributes`: select :guilabel:`Left` to display your product attributes on the left
  column, and select :guilabel:`Top` to display a :icon:`fa-sliders` (:guilabel:`dropdown toggle`)
  icon allowing users to filter products.

  - :guilabel:`Price Filter`: toggle the switch to display a :guilabel:`Price Range` bar which
    allows users to filter products according to a specific price range by dragging adjustable
    handles.
  - :guilabel:`Product Tags`: toggle the switch to display the :guilabel:`Product Template Tags` on
    the product page and allow customers to filter products using those tags by going to the
    :guilabel:`Tags` section in the left column.

- :guilabel:`Top Bar`: select :guilabel:`Sort By` to display a dropdown list in the top bar for
  sorting products and/or :guilabel:`Layout` to display the icons for :icon:`fa-th-large`
  (:guilabel:`Grid`) or :icon:`fa-list` (:guilabel:`List`) views.

- :guilabel:`Default Sort`: choose how to sort your products: :guilabel:`Featured`,
  :guilabel:`Newest Arrivals`, :guilabel:`Name (A-Z)`, :guilabel:`Price - Low to High` or
  :guilabel:`Price - High to Low`.

.. tip::
   To feature a product, go to the :ref:`product form <ecommerce-products-product-form>` and click
   the :icon:`fa-star-o` (:guilabel:`Favorite`) icon next to the product's name.

.. _ecommerce-products-product-page:

Product page
============

To access a product's page, go to your :guilabel:`Shop` and click on the product. Click
:guilabel:`Edit` to :ref:`customize <ecommerce-products-customization>` the page or
:ref:`edit its images <ecommerce-products-image-customization>`.

.. _ecommerce-products-product-form:

To access the backend **product form**, click the :icon:`fa-cog` :guilabel:`Product` button in the
top-right corner of the product page. Alternatively, navigate to :menuselection:`Website -->
eCommerce --> Products` and select your product. You can configure your product page from the form
by adding :ref:`variants <ecommerce-products-product-variants>`, :ref:`digital documents
<ecommerce-products-digital-files>`, or :ref:`translating <ecommerce-products-translation>` content.

.. tip::
   Click the :guilabel:`Go to Website` smart button to return to the frontend product's page.

.. _ecommerce-products-customization:

Customization
-------------

To customize a product page, click :guilabel:`Edit`. Go to the :guilabel:`Blocks` tab to add
:doc:`building blocks <../../websites/website/web_design/building_blocks>`.

.. tip::
   - When dragging and dropping a building block on your product page, placing it above or below the
     top or bottom blue lines makes it visible on all product pages.
   - You can edit any text on your website simply by clicking on it while in :guilabel:`Edit` mode.

Go to the :guilabel:`Customize` tab to modify the page layout or add features:

- :guilabel:`Terms and Conditions`: toggle the switch to display a link to your
  :doc:`terms and conditions <../../finance/accounting/customer_invoices/terms_conditions>` on the
  product page.

- :guilabel:`Customers`:

   - :guilabel:`Rating`: allows logged-in portal users to submit product reviews by clicking the
     stars below the product's name. The page automatically scrolls to the
     :guilabel:`Customer Reviews` section at the bottom, where users can share their experiences.
     Reviews are also visible in the product's chatter in the backend. To display reviews on the
     product page, click the :icon:`fa-plus` (:guilabel:`plus`) icon next to
     :guilabel:`Customer Reviews`. To restrict visibility to internal employees, toggle the
     :guilabel:`Public` switch next to the review comment.
   - :guilabel:`Share`: adds social media and email icon buttons allowing users to share the product
     through those channels.

- :guilabel:`Select Quantity`: toggle the switch to allow customers to select the product quantity
  they want to purchase.

- :guilabel:`Tax indication`: toggle the switch to indicate if the price is
  :ref:`VAT included or excluded <ecommerce-price-management-tax-display>`.

- :guilabel:`Variants`: show all possible :ref:`variants <ecommerce-products-product-variants>` of
  the product vertically as :guilabel:`Products List` or horizontally as selectable
  :guilabel:`Options` to compose the variant yourself.

- :guilabel:`Product Tags`: toggle the switch to display the :guilabel:`Product Template Tags` on
  the product page and allow customers to filter products using those tags.

- :guilabel:`Cart`:

   - :guilabel:`Buy Now`: adds a :icon:`fa-bolt` :guilabel:`Buy Now` button to take the customer to
     the checkout page.
   - :guilabel:`Wishlist`: adds an :icon:`fa-heart-o` :guilabel:`Add to wishlist` option allowing
     logged-in customers to save products in a wishlist.
   - :guilabel:`Compare`: adds a :icon:`fa-exchange` :guilabel:`Compare` option allowing users to
     :ref:`compare products <ecommerce-products-product-comparison>` based on their attributes.

- :guilabel:`Specification`: select :guilabel:`Bottom of Page` to display a detailed list of the
  attributes and their values available for the product. This option only works for products with
  :ref:`variants <ecommerce-products-product-variants>`, if the
  :ref:`Product comparison tool <ecommerce-products-product-comparison>` is enabled in the Website
  :guilabel:`Settings`.

.. note::
   - :guilabel:`Variants`, :icon:`fa-heart-o` :guilabel:`Wishlist`, and :icon:`fa-exchange`
     :guilabel:`Compare` options must be enabled by going to
     :menuselection:`Website --> Configuration --> Settings`, in the :guilabel:`Shop - Products`
     section.
   - Enabled functions apply to all product pages.
   - Products with single values for their attributes do not generate variants but are still
     displayed in the :guilabel:`Product Specifications`.

.. _ecommerce-products-image-customization:

Image customization
-------------------

To customize the images available on your product page, go to the :guilabel:`Customize` tab:

- :guilabel:`Images Width`: changes the width of the product images displayed on the page.
- :guilabel:`Layout`: the :guilabel:`Carousel` layout allows you to navigate from one image to the
  next using the :icon:`fa-angle-left` (:guilabel:`left arrow`) or :icon:`fa-angle-right`
  (:guilabel:`right arrow`); whereas the :guilabel:`Grid` displays four images in a square layout.
- :guilabel:`Image Zoom`: select the zoom effect for product images: :guilabel:`Magnifier on hover`
  :guilabel:`Pop-up on Click`, on :guilabel:`Both`, or :guilabel:`None`.
- :guilabel:`Thumbnails`: decide how the thumbnails should be aligned, either
  :icon:`fa-long-arrow-left` (:guilabel:`Left`) or :icon:`fa-long-arrow-down` (:guilabel:`Bottom`).
- :guilabel:`Main Image`: click :guilabel:`Replace` to change the product's main image.
- :guilabel:`Extra Images`: :guilabel:`Add` extra images or videos (including via URL) or
  :guilabel:`Remove all` product images.

.. note::
   Images must be in PNG or JPG format and with a minimum size of 1024x1024 to trigger the zoom.

.. _ecommerce-products-product-variants:

Product variants
================

:doc:`Product variants <../../sales/sales/products_prices/products/variants>` are different versions
of the same product, such as various colors or materials, with potential differences in price and
availability.

To configure product variants for your product:

#. Go to :menuselection:`Website --> Configuration --> Settings`;
#. Scroll down to the :guilabel:`Shop - Products` section and enable the
   :guilabel:`Product Variants` feature;
#. Access the :ref:`product forms <ecommerce-products-product-form>` and go to the
   :guilabel:`Attributes & Variants` tab, where you can add attributes and values, allowing customers
   to configure and select product variants on the product page. For multiple attributes,
   you can combine them to create specific variants.

.. note::
   To **restrict certain value combinations** and prevent customers from selecting them, click the
   :guilabel:`Configure` button on the attribute's line, click on a value, and in the
   :guilabel:`Exclude for` section, add a product in the :guilabel:`Product Template` and the
   :guilabel:`Attribute Values` to exclude.

To display or hide an attribute on the :guilabel:`Shop` page and allow visitors to filter them,
go to :menuselection:`Website --> eCommerce --> Attributes`, click on the attribute, and select
:guilabel:`Visible` or :guilabel:`Hidden` in the :guilabel:`eCommerce Filter Visibility`.

.. note::
   To display the product attributes on your Shop main page, go to your :guilabel:`Shop` page,
   click :guilabel:`Edit`, and set the :guilabel:`Attributes` feature to :guilabel:`left`.

To group attributes under the same section when
:ref:`comparing products <ecommerce-products-product-comparison>`, go to the
:guilabel:`eCommerce Category` field and either select an existing category or create a new one.

.. note::
   Two attribute values are needed to make the filter visible.

.. seealso::
   :doc:`Product variants <../../sales/sales/products_prices/products/variants>`

.. _ecommerce-products-digital-files:

Digital files
=============

You can link digital files like certificates, eBooks, or user manual to your products. These
documents are available :ref:`before payment <ecommerce-products-digital-files-before-payment>` on
the product page or in the customer portal :ref:`after checkout <ecommerce-products-digital-files-after-payment>`.

To link a digital file to a product, go to the :ref:`product form <ecommerce-products-product-form>`
and click the :guilabel:`Documents` smart button. Then, click :guilabel:`Upload` to upload a file
directly, or to get more options, click :guilabel:`New`, then :guilabel:`Upload your file`.

.. tip::
   - You can link a URL instead of a digital file. To do so, click :guilabel:`New`, go to the
     :guilabel:`Type` field, and select :guilabel:`URL`.
   - To edit an existing file, click the :icon:`fa-ellipsis-v` (:guilabel:`dropdown menu`) in the
     top-right corner of the document card and click :guilabel:`Edit`.

.. _ecommerce-products-digital-files-before-payment:

Digital files available before payment
--------------------------------------

To make the file available on the product page (before payment), leave the :guilabel:`Visibility`
field blank and toggle the :guilabel:`Show on product page` switch.

.. image:: products/digital-files.png
   :alt: digital file available before payment on the  product page

.. _ecommerce-products-digital-files-after-payment:

Digital files available after payment
-------------------------------------

To make your file available (after payment), set the :guilabel:`Visibility` field to
:guilabel:`Confirmed order` and turn off the :guilabel:`Show on product page` switch.

.. _ecommerce-products-translation:

Translation
===========

If multiple languages are available on your website, you can translate a product's information
directly on the :ref:`product form <ecommerce-products-product-form>`. Fields that support multiple languages
are identifiable by their abbreviation language (e.g., EN) next to their field.

.. image:: products/products-field-translation.png
   :alt: Field translation

The eCommerce-related fields to translate are:

- :guilabel:`Product name`;
- :guilabel:`Out-of-Stock Message` (under the :guilabel:`Sales` tab);
- :guilabel:`Sales Description` (under the :guilabel:`Sales` tab).

.. note::
   - Having untranslated content on a web page may be detrimental to the user experience and
     :doc:`SEO <../../websites/website/pages/seo>`. You can use the
     :doc:`Translate <../website/configuration/translate>` feature to allow automatic translation of
     standard terms and provide a tool for manual content translation.
   - To check the language(s) of your website, go to :menuselection:`Website --> Configuration -->
     Settings` and go to the :guilabel:`Website Info` section.

.. _ecommerce-products-website-availability:

Website availability
--------------------

To set the product's availability, navigate to the :ref:`product form <ecommerce-products-product-form>`, go
to the :guilabel:`Sales` tab, and in the :guilabel:`eCommerce shop` section, select the
:guilabel:`Website` you wish the product to be available on. Leave the field blank to make the
product available on *all* websites.

.. note::
   You can make a product available on either *one* website or *all* websites, but selecting only
   *some* websites is not possible.

.. _ecommerce-products-stock-management:

Stock management
================

To enable and configure inventory management options, go to :menuselection:`Website -->
Configuration --> Settings`, scroll down to the :guilabel:`Shop - Products` section and the
:guilabel:`Inventory Defaults` sub-section.

.. important::
   - The **Inventory** app must be installed to see the inventory management options.
   - To display the stock level on your product page, the :guilabel:`Product Type` must be set to
     :guilabel:`Storable` in the :ref:`product form <ecommerce-products-product-form>`.

.. _ecommerce-products-inventory:

Inventory
---------

In the :guilabel:`Inventory Defaults` sub-section, fill in those fields:

- :doc:`Warehouse <../../inventory_and_mrp/inventory/warehouses_storage/inventory_management/warehouses>`;
- :guilabel:`Out-of-Stock`: enable :guilabel:`Continue Selling` to allow customers to place orders
  even when the product is **out of stock**. Leave the box unchecked to **prevent orders**;
- :guilabel:`Show Available Qty`: displays the available quantity left under a specified threshold
  on the product page. The available quantity is calculated based on the :guilabel:`On hand`
  quantity minus the quantity already reserved for outgoing transfers.

.. _ecommerce-products-product-comparison:

Product comparison
==================

To allow website visitors to compare products based on their attributes, go to
:menuselection:`Website --> Configuration --> Settings`, scroll down to the
:guilabel:`Shop - Products` section, and enable :guilabel:`Product Comparison Tool`.

The :icon:`fa-exchange` (:guilabel:`Compare`) icon is now available on each product card on your main
shop page. Click the :icon:`fa-exchange` (:guilabel:`Compare`) option on the products you want to
compare. Then, click :icon:`fa-exchange` :guilabel:`Compare` in the pop-up window at the bottom of
the page to reach the comparison summary.

.. image:: products/products-compare.png
   :alt: Product comparison window

.. note::
   - The :guilabel:`Product Comparison Tool` is only available for products with
     :ref:`attributes <ecommerce-products-product-variants>`.
   - The :icon:`fa-exchange` (:guilabel:`Compare`) option can be specifically
     :ref:`added or removed <ecommerce-products-customization>` on each product page.

.. toctree::
   :titlesonly:

   products/catalog
   products/price_management
   products/cross_upselling
