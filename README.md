# Accept Subscriptions/Recurring payments with Stripe in ASP.NET & C#

![Subscriptions/Recurring payments with Stripe in ASP.NET](https://miro.medium.com/max/625/1*SsSmQbhb2UbdQQf_cSHPWA.png "This is image title")

With the Stripe Billing APIs, you can create and manage invoices and recurring payments.

You can now model your business and product offerings in one place. Products define what you sell and Prices track how much and how often to charge. They can be used for recurring or one-time purchases and support various business structures from tiers to usage based billing.

If you are looking a solution to integrate Stripe's subscriptions to your website (ASP.NET Web Forms or ASP.NET Core MVC) that is builded with .Net & C#, look at that demo → [https://techtolia.com/StripeSubscriptions/](https://techtolia.com/StripeSubscriptions/ "https://techtolia.com/StripeSubscriptions/")

Fixed-Price Subscriptions: Charge customers a fixed amount each month. The Quantity is set to 1.
Per-Seat Subscriptions: Charge customers based on how many units of your product or service they purchase. You must set the Quantity variable to the number chosen by your customer.


### How to model subscriptions
Learn how to model subscriptions using products and prices.

**Products and prices**
Products and Prices are the primary objects used to model subscriptions. Products define what you're selling and prices define how to charge for the product. For example, if you offer photo hosting for 15 USD a month, photo hosting is your product and the 15 USD a month is your price. Or, maybe you offer physical goods like a weekly produce box for 10 USD per week. The produce box is your product and the 10 USD is your price.

Products can have multiple prices so you can vary pricing by billing interval, currency, or amount. You can also use multiple prices to phase out old prices that you no longer offer.

Users commonly create and manage products and prices in the Stripe Dashboard. If you offer many products or plans, however, you might prefer to create these objects with the API.

In a fixed-price model, customers are charged the same amount every billing period. For example, a photo hosting company that offers basic and premium options might have:
* One product for the basic option
* One product for the premium option
* One price for the basic option (15 USD per month)
* One price for the premium option (25 USD per month)

In a per-seat model, customers are charged based on the number of seats or units that they purchase. For example, a messaging service that offers basic and premium options might have:
* One product for the basic option
* One product for the premium option
* One price for the basic option that charges the same amount per seat, regardless of the number of seats (5 USD per seat)
* One price for the premium option that includes tiers so that the price per-seat goes down the more seats that are purchased (tier one: 15 USD per seat for 1–100 seats, tier two: 10 USD for 101+ seats)



### Subscriptions with Stripe Elements
Build beautiful, smart checkout flows. Stripe Elements are rich, prebuilt UI components that help you create your own pixel-perfect checkout flows across desktop and mobile.


### Subscriptions with Payment Request Button
Collect payment and address information from customers who use Apple Pay, Google Pay, Microsoft Pay, and the browser Payment Request API (Chrome, Opera, Edge, Safari).

Customers see a "Pay now" button or an Apple Pay button, depending on what their device and browser combination supports. If neither option is available, they don't see the button. Supporting Apple Pay requires additional steps, but compatible devices automatically support browser-saved cards, Google Pay, and Microsoft Pay.



### What is Strong Customer Authentication?
Strong Customer Authentication (SCA) is a new European regulatory requirement to reduce fraud and make online payments more secure. To accept payments and meet SCA requirements, you need to build additional authentication into your checkout flow. SCA requires authentication to use at least two of the following three elements.

Banks will need to start declining payments that require SCA and don't meet these criteria. Although the regulation was introduced on 14 September 2019, we expect these requirements to be enforced by regulators over the course of 2020 and 2021.

3D Secure 2 - the new version of the authentication protocol rolling out in 2019 - will be the main method for authenticating online card payments and meeting the new SCA requirements. This new version introduces a better user experience that will help minimise some of the friction that authentication adds into the checkout flow.

*The application supports 3D Secure 2*

The Payment Intents API that uses Stripe's SCA logic to apply the right exemption and trigger 3D Secure when necessary.

*The application uses the Payment Intents API for card payments*



### Buy Now on CodeCanyon
**[Target Framework: .NET Framework 4.7.2 - Language: c#](https://1.envato.market/Xxy7Ma "Target Framework: .NET Framework 4.7.2 - Language: c#")**

**[Target Framework: .NET Core - ASP.NET Core 3.1 - Language: c#](https://1.envato.market/Zdb7M1 "Target Framework: .NET Core - ASP.NET Core 3.1 - Language: c#")**

