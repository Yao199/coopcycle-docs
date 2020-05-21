---
title: Managing a restaurant
lang: en
ref: admin-restaurant
parent: Restaurants
grand_parent: Admin's guide
nav_order: 2
---

# Managing a restaurant

## Restaurant information

The general information of the restaurant is accessible and modifiable at any time on the home page of the latter or from a tab by clicking on the link with the name of the restaurant at the top left of the page.

You will also find on this page **the terms of the contract** between the local delivery collective and the restaurant. They cover the following aspects:

- Delivery zone
- Delivery price
     - Package or percentage
     - Part to be paid by the.of the restaurateur.rice
     - Part to be borne by the. Of the final client.
- Minimum basket amount
- Payment fees (Stripe): paid by the platform or the restaurant owner

## Restaurant management pages

The different management pages of a restaurant are represented by tabs in the upper right corner of the restaurant page.


![Restaurant]({{ "/assets/images/restaurant_detail_fr.png" | absolute_url }})

- [Products](#products)
- [Options](#options-and-extras--adding-extras)
- [Menus](#menus)
- [Orders](#orders)
- [Schedule](#scheduling-opening-hours--closing-a-restaurant)


### Products

The product list allows you to record the different products that the restaurant delivers. The restaurateur must create the dishes that he makes available on the platform:
- the name of the product
- the description
- whether or not the product is activated
- the price and the tax applied

A product can have several associated options (see below), which must be created beforehand. For example a choice of ketchup, mayonnaise, white sauce for a portion of fries.

### Options and extras / Adding extras

The options allow you to make the products configurable. They allow for example to add supplements, or to choose the elements of a menu (accompaniment, drinks). A supplement is a list of products assigned to a product on the menu.

![Option]({{ "/assets/images/option_fr.png" | absolute_url }})

This list has the following characteristics:
- Last name
- Price calculation method
  - Free, no additional price for the supplement
  - Fixed price whatever the choice, the price is the same whatever the supplement chosen
  - Price depending on the choice, the price is variable depending on the chosen supplement
- Checkbox: is the supplement optional or not?

You must first create the necessary supplements in the dedicated tab using the "add" button before you can associate them with a product.
To assign a supplement to a product, simply activate it in a product in your restaurant. Go to the “product” tab of your restaurant, then click on the “modify” button of the product of your choice,
At the bottom of each product option, you will find the supplements that you previously created. You only have to tick the one or those of your choice.

### Menus

Each restaurateur can independently manage their card from their back office. Restaurants have the possibility of creating several menus and activating the one that corresponds to the need of the moment.

![Menu]({{ "/assets/images/menus_fr.png" | absolute_url }})

#### Creating a menu

In the "Menus" tab, you can create as many menus as you want. This allows you to configure menus in advance and easily activate the right one at the right time.

To create a menu, click the Add button. Then simply indicate the name of your menu and click on “save”. Your menu is ready to be configured! You can then activate your menu by clicking on the “Activate” button. A menu is indicated as activated by a check mark next to its name.

#### Adding a section to the menu

To configure your menu, you must first add one or more menu sections. For example: Starter, main course, dessert. To do this, enter the name of the section you want to create and click on “Add a section”.

#### Configuring a menu

Use the menu editor to compose add or remove products from the menu by dragging them - see below for creating a product. To make them available for sale you only have to drag and drop the products in the sections on the left. If you wish to withdraw a product from sale, drop it in the "Products" section on the right.

Do not forget to click on the "Save changes" button.

### Orders

All orders for a restaurant are available in the "order" tab of the restaurant. They are listed in the left pane by date of treatment. An order has a unique identifier, a status (new, validated, ready, canceled), a preparation date with a schedule, a summary and a price including tax. Click on an order present in the list to display its information.

In the right pane are displayed the information of the selected command. The dishes are listed there as well as the calculation of taxes. Finally, the buttons allow the restaurateur / administrator to accept or refuse the order. After indicating "accepted", the restaurateur must indicate that the order is ready. He can still at this stage cancel the order. Once the latter has been notified as ready, it is no longer possible to cancel an order.

### Scheduling opening hours / closing a restaurant

This feature allows you to temporarily close a restaurant. Scheduled closings are visible on the calendar.

### Behavior of opening hours

This feature allows you to determine how the client can choose the time of delivery.
"As soon as possible" will only allow her to order at the first time slot avalaible. 
"Time slot" will allow her to determine a time slot in advance for the delivery.

### Additional delay before ordering

This feature allows you to force clients to order with a minimum delay. 
For instance, if you want to have clients to order at least one day before the opening of the restaurant you can choose 1 day an 0 hours.

### Number of shipping choices (in days)

This parameter determines the maximum advance days for ordering a delivery. 

