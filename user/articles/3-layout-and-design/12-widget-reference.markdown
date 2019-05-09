# Commerce Widgets

Liferay Commerce ships with a wide range of widgets you'll use to construct
your site. This section provides a convenient overview in one place.

Accounts
:The Account Management widget allows buyers, sales agents and administrators to
manage their accounts without having to access to the control panel.

:Administrators can view a list of all accounts, create new accounts, delete
existing accounts, relate accounts to organizations, add members to accounts and
manage the roles and profile data of account members. Other roles can be given
fewer permissions.

Cart
:The Cart widget displays the cart's current contents. It includes controls to
change the quantity of the products it holds, or to delete them entirely.

Cart Summary
:The Cart Summary widget displays the total price of all items in the cart,
including a *checkout* button. It doesn't list the cart's contents.

Mini Cart
:The Mini Cart displays the cart's contents and includes a checkout button, but
has no controls to edit its content. Instead, it displays an *Edit Cart* button
that links to the Cart widget. Because of this link, the Mini Cart can't
function unless a page containing a Cart widget is present.

Open Carts 
:The Pending Orders widget displays orders that have not been submitted to the
seller. The Cart widget's current contents are included as a pending order, as
well as any orders that are in the process of a buyer-side workflow.

Category Content
:The Category Content widget identifies a category page to other widgets and
selects content appropriate to the context. This allows a single page to
represent all of a site's product categories.

:When a user selects link to a product category, Category Content displays
content based on the category selected. By default, the widget will display
whatever image is assigned to the category.

:If you place a Search Results widget on the same page, Category Content will
point the search widget toward products in the selected category.

Checkout 
:The checkout widget handles the purchase process. Without any configuration,
the Checkout widget features a four-step process: shipping address, billing
address, order summary and order confirmation. When you configure [Shipping
Methods](/web/liferay-emporio/documentation/-/knowledge_base/1-0/shipping-methods)
and [Payment
Methods](/web/liferay-emporio/documentation/-/knowledge_base/1-0/payment-methods),
additional steps are automatically added to the process.

:Custom checkout steps can be added using the [custom checkout step extension
point](/web/liferay-emporio/documentation/-/knowledge_base/1-0/custom-checkout-step).

Commerce Categories Navigation 
:The Commerce Categories Navigation widget displays link to each product
category. 

:The widget displays a link for every category within a selected vocabulary.
Each link provides context to the category page so that the correct content is
displayed.

Orders 
:The Orders widget displays a list of placed orders. Each order can be selected
to display additional information about the transaction, with an option to
reorder.

Coupon Code Entry 
:The Coupon Code Entry widget provides a field for buyers to enter a coupon
code.

:See
[Discounts](/web/liferay-emporio/documentation/-/knowledge_base/1-0/discounts)
for more on coupon codes.

Product Comparison Table 
:The Product Comparison Table displays information on different products
side-by-side.

Product Comparison Bar
:The Product Comparison Bar adds products to the Product Comparison Table.

:When placed on a product page, this widget modifies the Product Detail widget
to include a *Compare* button. Clicking it adds the current product to Bar.
Clicking the Bar's *Compare* button navigates to the Product Comparison Widget
and displays selected products side-by-side.

Product Details 
:The Product Details widget displays information about a product. When a user
clicks on a link to a product page, the widget retrieves the appropriate content
from the catalog and displays it on the page. 

:Rather than forcing you to configure a unique page for every product, the
widget allows you to use a single page,  reading the current context to
determine what product's information should be displayed.

Product Downloads 
:The Product Downloads widget displays a list of files that a user can download.
When a user purchases a virtual product with a downloadable file attached, that
file can be retrieved from the Product Downloads widget.

Product Publisher 
:The Product Publisher displays a list of products. You can select products
manually, or configure so Commerce can make the selection for you.

-   Dynamic selection: Publish products associated with certain categories and
    or tags. From the Configuration screen, open the *Filter* section and
    specify what categories or tags you want to publish or exclude from
    publishing.

-   dataSource selection: Select a criterion (for example, *Products of the same
    Category*) that will be applied depending on the current context. 
 
Product Subscriptions
:Allows buyers to track and manage subscriptions.

Search Results
:The Commerce &rarr; Search Results widget displays products in response to
a search query. Not to be confused with the Search &rarr; Search Results widget,
which returns assets of all types.

Option Facet
:Displays facets for filtering search results by product option.

Specification Facet
:Displays facets for filtering search results by product specification.

Shipments
:Displays shipment information to buyers. The information displayed by the
Shipments widget must be entered in the Shipments administrative portlet in
*Site Menu* &rarr; *Commerce* &rarr; *Shipments*.

Wish Lists 
:Wish Lists allows buyers to create lists of products to track. The Wish Lists
widget displays the current user's wish lists. Users can add or delete lists, or
select one to display its contents.

Wish List Contents
:Displays the contents of the wish list selected by a Wish Lists widget on the
same page.
