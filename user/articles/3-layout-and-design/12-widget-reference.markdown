# Commerce Widgets

Liferay Commerce ships with a wide range of widgets you'll use to construct
your site. This section provides a convenient overview in one place.

## Account Management

The Account Management widget enables users to add or edit accounts. Future
iterations of @commerce@  will enable administrators to edit accounts from the
control panel, but the widget will facilitate allowing buyers and other users to
manage their accounts without granting them access to the control panel.

The widget's display varies depending on the context: it will show
administrators all existing accounts, while users with appropriate permissions
will see a list of accounts that they are able to edit. Users with no such
permissions will see only their personal accounts.

![Figure 1: Users can add members, addresses, and other information to an
account.](../../images/account-management.png)

## Cart Widgets

There are three cart widgets: the Cart, the Mini Cart and the Cart Summary.

The **Cart** widget displays the cart’s current contents. It includes controls to
change the quantity of the products it holds, or to delete them entirely.

The **Cart Summary** widget displays the total price of all items in the cart,
including a checkout button. It doesn’t list the cart’s contents.

![Figure 2: A typical approach places the Cart and Cart Summary on the same page. This example also includes a Coupon Code Entry widget (see below) as well.](../../images/cart-and-summary.png)

The **Mini Cart** displays the cart’s contents and includes a checkout button,
but has no controls to edit its content. Instead, it displays an Edit Cart
button that links to the Cart widget. Because of this link, the Cart Mini
widget can’t function unless page containing a Cart Content widget is present.

![Figure 3: The Mini Cart displays the contents of the cart at a glance, along with a quick link to the main cart page.](../../images/mini-cart.png)

## Category Content

The Category Content widget identifies a category page to other widgets, and
selects content appropriate to the context.

For example, when a user selects a category using *Category Navigation*, the
navigation widget finds the first page with a Category Content widget and
displays it. Category Content then displays appropriate content based on the
category selected: for example, by the default the widget will desplay whatever
image is assigned to the category in (set in *Site Menu* &rarr;
*Categorization*)

If you place a Search Results widget on the same page, Category Content will
point the search widget toward products in the selected category.

![Figure 4: Category Content displays the heading for the category and populates the Search Results widget beneath it.](../../images/category-content.png)

## Checkout

The checkout widget handles purchase process. Without any configuration, the
*Checkout* widget features a four-step process: users are prompted to enter a
shipping address, a billing address, an order summary, and finally an order
confirmation. When you configure [Shipping
Methods](/web/liferay-emporio/documentation/-/knowledge_base/1-0/shipping-methods)
and [Payment
Methods](/web/liferay-emporio/documentation/-/knowledge_base/1-0/payment-methods),
additional steps are added automatically to the checkout portlet's process,
prompting users to select one of each.

![Figure 5: Checkout offers users a familiar experience out of the box.](../../images/checkout.png)

Additional checkout steps can be customized. Details 
[here](/web/liferay-emporio/documentation/-/knowledge_base/1-0/custom-checkout-step).

## Commerce Categories Navigation

The Commerce Categories Navigation widget works with [Category
Content](#category-content) facilitate navigation to product category pages.

![Figure 6: On the surface, categories navigation is just a list of links.](../../images/commerce-categories-navigation.png)

Select a vocabulary on the widget's configuration screen. All of the categories
in that vocabulary will be displayed by the widget as links to category pages.
When a user selects one of those links, that selection is provided as context
to the Category Content widget, which then displays the desired category.

## Orders

At present, Commerce Order Content and Pending Orders are two separate widgets.
In a future version, @commerce@ will combine them into one widget which will be
configurable to display either past or pending orders.

### Commerce Order Content

The Order Content widget displays information about past orders: when it was
created, who placed it, it's current status, etc. Click on an order to display
additional information about the transaction, with an option to reorder.

### Pending Orders

The Pending Orders widget, meanwhile, displays orders that have not been
placed. The cart's current contents are included as a pending order, as well as
any orders that are in the process of a buyer-side workflow.

![Figure 7: Pending Orders is intended particularly for B2B purchasers who need to generate orders and then store them while waiting for approval.](../../images/pending-orders.png)

## Coupon Code Entry

If you've created a discount that requires the entry of a coupon code, then
buyers who know the code will need something to do with it. Drop a coupon code
widget onto a page--sharing a page with Cart or Pending Orders is logical, but
you can put it anywhere a buyer will have access prior to completing an order.

![Figure 8: Here a buyer can enter a coupon code right before checking out.](../../images/cart-and-summary.png)

See
[Discounts](/web/liferay-emporio/documentation/-/knowledge_base/1-0/discounts)
for more on coupon codes.

## Product Comparison Table 

Displays the information for different products side-by-side. The Product
Comparsion Bar---see below---is used to add products to the table.

![Figure 9: A conventional approach would place the Comparison Table on its own page.](../../images/product-comparison-table.png)

### Product Comparison Bar

When placed on a product page, this widget modifies the Product Detail widget
to include a *Compare* button. Clicking it adds the current product to the
compare products widget. Clicking the *Compare* button on the Compare Products
Mini widget navigates to the Compare Products widget and displays selected
products side-by-side.

![Figure 10: In this example, the widget is styled as a popup to avoid taking up real estate when no products have been selected.](../../images/product-comparison-bar.png)

## Product Details

The Product Details widget displays information about a product.When a user
clicks on a link to a product page, the widget retrieves the appropriate
content from the catalog and displays it on the page. 

![Figure 11: The content displayed depends on the widget's configuration, but by default it includes the product’s images, description, and price, and an *Add to Cart* button.](../../images/product-details.png)

Product Details works much like Category Content (see above). Rather than
forcing you to configure a unique page for every product, the widget allows you
to use a single page where the widget simply reads the current context
to determine what product's information should be displayed.

## Product Downloads

For Virtual Products

## Product Publisher

The Product Publisher simply displays a list of products. You can select
products manually, or provide criteria so Commerce can make the selection for
you.

![Figure 12: Product Publisher can be configured to select products according to a variety of criteria.](../../images/product-publisher.png)

-   Dynamic: Publish products associated with certain categories and or tags.
    From the Configuration screen, open the *Filter* section and specify what
    categories or tags you want to publish or exclude from publishing.

    ![Figure 13: You can excercise precise control over what is displayed by creating any number of rules.](../../images/product-publisher-2.png)

-   dataSource: Select a criteria that will be applied depending on the current context.

    ![Figure 14: For instance, select *Products Of the Same Categories*. If the Product Publisher shares a page with Product Details, it will display products sharing categories with the product display by the other widget.](../../images/product-publisher-3.png)

## Product Subscriptions

For the buyer to track his subscriptions

## Search Results

To be merged with Search's search results? For now, it only finds products

### Option Facet

Group with search results

### Specification Facet


## Shipments

## Wish List Contents

Used for editing and viewing the content of a single wishlist. It looks like the typcial use case is to put both of these widgets side-by-side on a page.

## Wish Lists

A wishlist isn't so much a wishlist as a list of products that a buyer might
want to track.

The My Commerce Wish List widget manages wish lists--whatever wish lists you
have access to. If you're an administrator, that's all of them.




