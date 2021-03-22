# Yuki Ishii

## A French pastry online shop "Un Delice"

This project aims to create a website for a French pastry shop, located in Dublin. The business is selling 2 types of product:
* **the patisserie**: the general French pastries (ex: Mille-Feuille, Eclair)
* **the viennoiserie**: it is a category of pastry, a mix between pastry and bakery (ex: croissant, pain au chocolat).

The design of the website is simple and clear so that the customer can navigate and read easily all the information on each different page. The customer can choose between two options to receive the order: collection at store or delivery.

## Table of contents
1. [UX](#ux)   
a.[Strategy plane](#strategy-plane)  
b.[Scope plane](#scope-plane)  
c.[Structure plane](#structure-plane)   
d.[Skeleton plane](#skeleton-plane)    
e.[Surface plane](#surface-plane) 

2. [Technologies used](#technologies-used)  

3. [Testing](#testing)

4. [Deployment](#deployment)

5. [Credits](#credits)
---
## UX <a name="ux"></a>

### Strategy plane <a name="strategy-plane"></a>
---
The main goal of the website is to make known the French pastry in Ireland by building an online shop site.
The business targets potentials clients who are living in Dublin or passing in the city.

#### The Ideal clients: 
* Clients who like the desert, sweet.
* Clients from France living in Dublin and want to find a French pastry shop.
* Clients who want to discover a new type of pastry.
* Clients who are living within Dublin 1 and 24 or visitors, tourists who are currently in this area.

#### The goal & need of the client:
**Goal**:
* Get easily and clear information about the shop on all devices.
* Purchase in few steps 

**Need**:
* Know what contains the product, the flavor, the allergen, and the price.
* Information about ordering process: the collection and delivery option, the contact details, location.
* Find the social media link to stay up to date.

#### The goal & need of the business:
**Goal**:
* Promote the shop, make known the French pastry.
* Provide good experience to keep customer
* Increase customers 

**Need**:
* Advertise the product through the website and social media. 
* Provide clear information on the website for a good user experience.

#### User Stories
* As a **first-time visitor**, I want information about French pastry so I know what is the patisserie and viennoiserie.
* As a **first-time visitor**, I want to view the list of pastry available so I can check the price, the allergens, the flavor.
* As a **first-time visitor**, I want to easily navigate the site so I can get clear information quickly.
* As an interested client, I want to know the ordering process so I can receive the product.   
* As an **interested client**, I want to know how and when I can receive my order so I can choose between collection or delivery and select a suitable time.
* As an **interested client**, I want to get information about the shop so I can check the contact details, the location, the opening hour.
* As a **returning customer**, I want to follow the shop on social media so that I can stay up to date with the latest news of the shop.

### Scope plane <a name="scope-plane"></a>
---
#### Features

##### Existing features
* A navigation bar in all the pages with the name of the shop on the left and on the right four clickable options: **Home**, **our product** with the dropdown giving the option to choose patisserie and viennoiserie, **order online** and **our store**.
The navigation bar is fixed so it keeps displaying when the user scrolls down.
On the mobile device, the content of the navbar is hidden and will be displayed if the click on the icon.

* A footer on each page: from the left, the name of the business, the contact details, the location, and social medial link.   
On the mobile device, the name of the business is not displayed.

* On the home page, a subscription button to get delivery free in the first order by entering the email address and the customer has the option to agree to receive a marketing email.

* On the home page, a link "our selection" under the patisserie and viennoiserie info to direct to the page of the type of product selected.

* The patisserie and viennoiserie page allows the customer to view the product available with brief information with the price and allergens.

* The order online page allows the customer to order by filling in a form with the customer details, the product selected, and the option to choose collection and delivery.

* When the customer chooses between the collection and delivery option in the order form, it allows to choose a date and time in both options, and in the delivery option, the customer can enter a delivery address.

* On the store page, the customer can view the picture of the shop and the pastry chef. There is a google map with the address of the shop and opening hour.

##### Features Left to Implement
* For the moment, in the form order, the modal is used to show the confirmation order message. Even though there is a missing field, it will display the modal message.  
To not allow to submit when there is a missing field, javascript is needed.

* Add Terms of use, privacy policy, and copyright.

* Add shopping cart and payment option: Javascript or PHP needed

* FAQ pages to get all important information needed: Javascript or PHP needed

* Create a search bar so if the customer types keyword, will appear several choices on the page related to this keyword: Javascript needed



### Structure plane <a name="structure-plane"></a>
---
#### Home
On the home page on the top, to make a first good impression, it has a full-width image with a minimal sentence in the middle so that the website is more catchy and compelling.  
Underneath, an input for an email address with a subscribe button. For the marketing aim, the business wants to offer free delivery on the first order. When the user clicks on the subscribe button, a modal message will display with the option to receive marketing communication if the user wants.   
Below, there is a brief description of the patisserie and viennoiserie.  
In the end, a brief explanation about the delivery.

#### Our product (2 pages)
By clicking on **our product** in the navbar, it displays two option clickables: the patisserie and viennoiserie and will load the page selected.
The layout of these two pages is the same. The list of the product will be displayed in three columns on a desktop, and Ipad pro.
On a mobile device and Ipad, it will show two columns.
In each product, there will be the image, the price, the flavor, taste, and the allergen.

#### Order online
On the top of this page, an explanation about the ordering process and collection, delivery option.

Underneath, a form of the order details: 
* In the first part, the details of the customer.
* In the second part, an input number beside the name of the product to select the amount. 
Under the patisserie and viennoiserie, a link to direct to the list of the product page into the new browser.
So if the customer doesn´t remember how the product looks like, by clicking on the link, the customer can check again to be sure about the product selected.
* At the end of the form, the customer has to select between the collection or delivery options. 
Both options contain hidden div, so if the customer selects the delivery option, it will appear the date, time, and address to fill out. If the collection option is selected, it only appears the date and time to choose.

When the customer will confirm the order, it will display a modal message. By clicking on the button "close" of the modal, it will redirect to the home page.

#### Our store
On this page, one picture of the shop and one picture of the pastry chef. Under the picture of the pastry chef, a brief explanation about this chef and the shop.
Above, it displays a google map with the address of the shop including the opening hours.

### Skeleton plane <a name="skeleton-plane"></a>
---
#### Wireframe

[Home page](https://github.com/yuyu78/pastry-online-shop/blob/master/wireframe/home-page.pdf)

[Subcription home page](https://github.com/yuyu78/pastry-online-shop/blob/master/wireframe/subscription-home-page.pdf)

[Product page: Patisserie and Viennoiserie](https://github.com/yuyu78/pastry-online-shop/blob/master/wireframe/our-product-dropdown-patisserie-viennoiserie.pdf)

[Order online form](https://github.com/yuyu78/pastry-online-shop/blob/master/wireframe/order-online-form.pdf)

[Our store](https://github.com/yuyu78/pastry-online-shop/blob/master/wireframe/our-store.pdf)

[Confirmation order](https://github.com/yuyu78/pastry-online-shop/blob/master/wireframe/confirmation-order.pdf)

At the beginning of the project, the plan was to create a confirmation order page separately when the customer submits the order but because Javascript is needed, instead, a modal message has been used so that when the customer clicks on "confirm order", it will display the modal message for the confirmation purchase.

### Surface plane <a name="surface-plane"></a>
---
#### Color Scheme
The main colors of the website are: 
* White
* Beige for the background color of the navbar and footer
* Orange-brown for the name of the brand "Un Delice"

For the pastry website, the choice of these colors is  justified by easier and clear navigation for the customer and highlight the products.

#### Typography 
* **Poppins** in all the page in general
* **Parisienne** for the name of the shop
* **Crimson Pro** for the navbar 
* **Alegreya** at the end on the footer on "French Pastry"

#### Imagery
All the images were taken from [Unplash](https://unsplash.com/) and [Pexels](https://www.pexels.com/).

---
## Technologies Used <a name="technologies-used"></a>
---
* **HTML5** and **CSS3** programming languages.
* [Git](https://git-scm.com/) for version control
* [Github](https://github.com/) to store repositories.
* [Gitpod](https://www.gitpod.io/), for the workspace. 
* [Balsamiq](https://balsamiq.com/wireframes/) to create a mockup.
* [Bootstrap](https://getbootstrap.com/) version 4.3.1, a framework to make the website responsive easier.
* [Jquery](https://jquery.com/) and [Popper JS](https://popper.js.org/) to use navbar, dropdown and modal from bootstrap 
* [Google fonts](https://fonts.google.com/) to choose font family for the website 
* [Fontawesome](https://fontawesome.com/) for icon
* **Google Chrome Dev tools** to fix bug
* [HTML Validator](https://validator.w3.org/) to validate HTML codeç
* [CSS Validator](https://jigsaw.w3.org/css-validator/) to validate CSS code
* [Grammarly](https://app.grammarly.com/) to check spelling mistake
---
## Testing <a name="testing"></a>
---

The testing process can be found [here](https://github.com/yuyu78/pastry-online-shop/blob/master/TESTING.md)

---
## Deployment <a name="deployment"></a>
---
Gitpod was used to develop the project and deployed through Github Pages.   

The steps for the deployment of the project:

1. Login to [Github](https://github.com/)  
2. Click on the green and white icon on top-right and select "Your repositories"  
3. From the list of the repositories, select **pastry-online-shop**  
4. Click on **Settings**  on the right of the menu items  
5. Scroll down to the **GitHub Pages**  
6. Under source in the dropdown menu, select **Master**
7. On the right, select the folder **/(root)**  
8. Click **Save** and the page will automatically refresh  
9. Scroll back again to the **GitHub Pages** and click on the link to the deployed site

### To run the project locally  

1. Go to the repository [pastry-online-shop](https://github.com/yuyu78/pastry-online-shop)  
2. Click to the green button **Code** and select **Download ZIP**
3. Extract the file downloaded to run the project locally
---
## Credits <a name="credits"></a>
---

### Inspiration
* The layout of the homepage is inspired by the pastry site [Dolcesicily](https://shop.dolcesicily.ie/)  and [Thundersbakery](https://thundersbakery.ie/). Both homepages of these two websites start with a hero image with full width. On the website of [Dolcesicily](https://shop.dolcesicily.ie/), the idea of one picture and one paragraph in each row was taken to explain clearly the patisserie and viennoiserie.
* Inspired from the README and TESTING file template of [Anna Gilhespy](https://github.com/AJGreaves/portrait-artist)
* Inspired from the template of [Code Institute](https://github.com/Code-Institute-Solutions/SampleREADME)
* The information about the products was found on Wikipedia.

### Code
* Navbar from [Bootstrap](https://getbootstrap.com/docs/4.1/components/navbar/)
* Modal from [Bootstrap](https://getbootstrap.com/docs/4.1/components/modal/)
* Spacing from [Bootstrap](https://getbootstrap.com/docs/4.1/utilities/spacing/)
* The social media section on the footer was inspired by the **Code Institute course with the Mini Project with Bootstrap 4**
* Form from [Bootstrap](https://getbootstrap.com/docs/4.1/components/forms/)
* The solution to remove the space on the right in the home page on mobile device: from [stackoverflow](https://stackoverflow.com/questions/46012482/unwanted-white-space-on-right-side-in-mobile-view/46012924)
* To display two columns on mobile and three columns on desktop in the patisserie and viennoiserie page: found solution from [stackoverflow](https://stackoverflow.com/questions/21790409/3-columns-on-desktop-to-2-columns-on-tablet/21790525)
* To reveal and hide div element with the radio button in the order form, inspired from [stackoverflow](https://stackoverflow.com/questions/21790409/3-columns-on-desktop-to-2-columns-on-tablet/21790525)
* To fix the issue of the radio button to allow to choose only one option, solution found in [stackoverflow](https://stackoverflow.com/questions/5419459/how-to-allow-only-one-radio-button-to-be-checked/5419479)

### Media
All the image are from [Unplash](https://unsplash.com/) and [Pexels](https://www.pexels.com/)

### Acknowledgment 

* My mentor Miguel who provided advice and feedback during the project
* All the tutor of Code Institute
* Code Institute Slack community 