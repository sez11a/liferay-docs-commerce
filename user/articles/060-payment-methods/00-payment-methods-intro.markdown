---
header-id: payment-methods
---

# Payment Methods

[TOC levels=1-4]

@commerce@ offers one payment method---money order---that does not require the
services of a third-party payment provider. Integration with payment providers
is also possible, with three---PayPal, Mercanet, and Authorize.net---ready to go
out of the box.

## Money Order

While there are obvious downsides to money orders---starting with the time it
takes to deliver payment through the mail---the payments are widely used in some
circles, and not necessarily only by low-tech firms. Follow these steps to allow
customers to pay by money order:

1.  Go to *Site Menu* &rarr; *Commerce* &rarr; *Settings* and click the
    *Payment Methods* tab.

2.  Click *Money Order* and fill in the following fields:

    **Name**: Give the payment method a name, or leave it as *Money Order.*

    **Description**: Text entered in this field appears on the screen where
    buyers select a payment method.

    **Icon**: Hit *Browse* to upload or select an image to display along with
    the name and description.

    **Priority:** Set a priority to determine the order payment methods appear
    on a page. Lower numbers come first.

    **Message**: Text entered here is displayed after the customer chooses the
    money order option. This text tell customers where to send the money order,
    provide a shipping time estimate, or the like.

3.  Set the *Active* toggle to *yes* and click *Save*.

## PayPal

Follow these steps to let buyers pay with PayPal:

1.  Go to the
    [PayPal Developer
    Dashboard](https://developer.paypal.com/developer/applications/create) and
    obtain a Client ID and Client Secret. You must open an account and create
    a PayPal REST API application.

2.  Back in @commerce@, go to *Site Menu* &rarr; *Commerce* &rarr; *Settings*
    and click the *Payment Methods* tab.

3.  Click *PayPal* and fill in the following fields:

    **Name**: Give the payment method a name, or leave it as *PayPal.*

    **Description:** Text entered in this field appears on the screen where
    buyers a select a payment method.

    **Icon**: Hit *Browse* to upload or select an image to display along with
    the name and description.

    **Priority:** Set a priority to determine the order payment methods appear
    on a page. Lower numbers come first.

4.  Enter the Client ID and Client Secret into the appropriate fields. Then
    select a *Mode* (*Sandbox* for testing, *Live* for actual transactions),
    check the *Active* box, and click *Save*

## Mercanet

Follow these steps to let buyers pay with Mercanet.

1.  Go to [Mercanet](https://documentation.mercanet.bnpparibas.net/index.php?titl
e=Obtenir_sa_cl%C3%A9_secr%C3%A8te#) to obtain a Mercanet Merchant ID, Secret
Key, and a Key Version.

Because Mercanet accepts only EUR, the store's primary currency must be EUR. To change the primary currency:

2.  Back in @commerce@, go to the *Control Panel* &rarr; *Commerce* &rarr; *Settings*.

3.  Click _Currencies_.

4.  Click the _3-dot icon_ next to *Euro*.

5.  Click _Set as Primary_.

Once the store's primary currency has been changed, Mercanet can now be used.

1.  Go to *Site Menu* &rarr; *Commerce* &rarr; *Settings*
    and click the *Payment Methods* tab.

2.  Click *Mercanet* and fill in the following fields:

    **Name**: Give the payment method a name, or leave it as *Mercanet.*

    **Description:** Text entered in this field appears on the screen where
    buyers a select a payment method.

    **Icon**: Hit *Browse* to upload or select an image to display along with
    the name and description.

    **Priority:** Set a priority to determine the order payment methods appear
    on a page. Lower numbers come first.

4.  Set the *Active* toggle to *yes* and click *Save*.

5.  Click the *Configuration* tab.

6.  Enter the Merchant ID, Secret Key, and Key Version into the appropriate fields. Then
    select an *Environment* (*Simulation* or *Test* for testing, *Production* for actual transactions),
    and click *Save*


## Activate.net

Follow these step to let buyers pay with Activate.net

1. Go [Activate.net](https://support.authorize.net/s/article/How-do-I-obtain-my-
API-Login-ID-and-Transaction-Key) and obtain an API Login ID and a Transaction
Key.

2. Back in @commerce@, go to *Site Menu* &rarr; *Commerce* &rarr; *Settings*
    and click the *Payment Methods* tab.

3. Click *Activate.net* and fill in the following fields:

    **Name**: Give the payment method a name, or leave it as *Activate.net*.

    **Description:** Text entered in this field appears on the screen where
    buyers a select a payment method.

    **Icon**: Hit *Browse* to upload or select an image to display along with
    the name and description.

    **Priority:** Set a priority to determine the order payment methods appear
    on a page. Lower numbers come first.

4.  Set the *Active* toggle to *yes* and click *Save*.

5.  Click the *Configuration* tab.

6.  Enter the API Login ID and Transaction Key into the appropriate fields. Then
    select an *Environment* (*Sandbox* for testing, *Production* for actual transactions),
    and the check the appropriate boxes for *Display* options and *Security* options.

7. Click *Save*.
