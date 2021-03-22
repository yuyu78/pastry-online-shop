# TESTING French Pastry online shop "Un delice"

## HTML CSS validator
---
Checked the validity of the code with [HTML Markup Validation Service](https://validator.w3.org/) and [CSS Validation Service](https://jigsaw.w3.org/css-validator/) and there were no errors.

However, with the code of the [order page](https://github.com/yuyu78/pastry-online-shop/blob/master/order.html), there is a warning about using the heading element h2-h6 in the sections.

![image](https://user-images.githubusercontent.com/76018052/111849799-c7d36700-890e-11eb-9b75-91531d19eac5.png)

Instead of the section, the semantic div was replaced so that there is no warning.

## Devices tested
---
Devices tested during the project: 
* Desktop
* Moto G4 
* Galaxy S5
* Pixel 2
* Pixel 2Xl
* Iphone 5/SE 
* Iphone 6/7/8
* Iphone x
* Ipad 
* Ipad Pro
* Surface Duo

## Testing User Stories
---
1. As a first-time visitor, I want information about the French pastry so I know what is the patisserie and viennoiserie.      
    * When the visitors land on the home page, they get a brief explanation about the two types of pastries: patisserie and viennoiserie.  
    * Under these two types of pastries, there is a button to direct to the list of product 

2. As a first-time visitor, I want to view the list of pastry available so I can check the price, the allergens, the flavor.     
    * The visitor can view the list of products on the patisserie and viennoiserie page through the button "our selection" under the brief explanation on the home page.  
    * The visitor can click the link "our product" on the navbar and choose between patisserie and viennoiserie.

3. As a first-time visitor, I want to easily navigate the site so I can get clear information quickly.   
    * The links of the navbar are clear with the home page, our product with two options: patisserie and viennoiserie page, order page, and store page.  
    * There are clear information in the home page about the pastries, order, collection, delivery option if ordering online.  
    * On the footer, the contact, location, and social media link.   
    * The same navbar and footer on each page so the visitor can easily navigate to a different page.

4. As an interested client, I want to know the ordering process so I can receive the product.  
    * There is a link order online on the navbar.  
    * On the top of the order page, there is a requirement about the ordering process.  
    * the client can get free delivery in the first order from the home page by subscribing and enter the same email address in the form order.  
    * The visitors have to fill in their information, choose the product available and select between collection and delivery.  
    * The name of the French pastries is not obvious to every customer.   
    That is why there is a link under the patisserie and viennoiserie in the order form so that if the clients don´t remember how the product looks like, they can simply click on the link and will open another browser separately to check again the list of product during the ordering process.

5. As an interested client, I want to know how and when I can receive my order so I can choose between collection or delivery and select a suitable time.    
    * The clients can order at the store or online.  
    * If the clients order online, they can choose the two options between collection and delivery.  
In both options, the clients can select a date.

6. As an interested client, I want to get information about the shop so I can check the contact details, the location, the opening hour.    
    * The client can get information about the shop, the address with google maps, the number, and opening hours, by clicking "our store" in the navbar.  
    * The client can get contact information and location in the footer. Besides the address location, there is an icon that directs to the google map.

7. As a returning customer, I want to follow the shop on social media so that I can stay up to date with the latest news of the shop.  
    * The clients can find the social media link on the footer.  
    * The clients can also agree to receive marketing communication if they enter the email and subscribe on the home page, in the modal message.

## Manual Testing
---

* The Navigation all the pages:  
1.When navigating to one the theses pages: **"Home"**, **"Our product"** with the dropdown to allow to select patisserie and viennoiserie page, **"Order online"**, **"Our store"**, verify if it underlines the link of the current page.  
2.Hover over the link and check if the background changes in grey.  
3.Check if the name of the shop is clickable and direct to the home page.  
4.Check if on the mobile device, the icon of the navbar collapse.

* Footer in all the pages:  
1.On Ipad, the email icon and email address were not aligned.  
To fix the issue, change the font-size of the p tag in the footer to 0.9rem.  
![image](https://user-images.githubusercontent.com/76018052/111865126-80c49080-8965-11eb-94d6-87562aee5088.png)  
2.Check if, on the mobile device, the name of the brand is hidden so that the footer is visually better and not too long vertically.  
3.The social media icons were not displaying because, in the head element, the link https://kit.fontawesome.com/47aa28a2ac.js with the kits was used but put the icon of the latest version.  
The issue was fixed when using the icon from the kits.  
4.When clicking on the social media icon and the maps in the location, check if it opens a new browser and directs to the page linked.

* Home page  
1.On a mobile device, there was a little space on the right of the hero image.  
![image](https://user-images.githubusercontent.com/76018052/111877739-edab4b00-89a4-11eb-8ccf-83c3633de0d5.png)  
To fix the issue, add in CSS in HTML and body element the code "overflow-x: hidden;".  
2.Check if the height of the hero image is well adjusted on mobile, Ipad, desktop.  
3.Verify if the modal message is working.  
4.Hover over the button "subscribe", "our selection" and check if the color change.  
5.Check if the button "our selection" under  the patisserie and viennoiserie directs to the correct product page.  
6.Change the screen on the mobile size and verify if all the information displays vertically in one column.  

* Our product: Patisserie an Viennoiserie  
1.Check if the layout of both pages is the same.  
2.Check that there is a space between products so that the page looks clear and not overwhelming.    
3.Verify on the mobile device and Ipad that it displays two columns in each row.  
The issue was on desktop size, it couldn´t display in three columns as planned. To fix this issue, all the products in the code were put in the same row and the columns were adjusted within the class element with the grid system of bootstrap.

* Order online page  
1.Check if the form is responsive on all the devices, desktops.  
2.Check if the link under the patisserie and viennoiserie direct to the page related.  
3.There was an issue with the collection and delivery option, the radio buttons didn´t work correctly.  
The form order still allowed to choose both options even though the input type was "radio", the aim was to allow to choose only one option. The issue happened because the name of the input was different so change and put the same name of the input collection and delivery (name="selection") to fix the problem.  
4.Try to submit the form: the modal message is showing correctly but even though there is "required" in the input, it still shows the modal message even though there is some missing field. The javascript is required in this case to allow to submit correctly the form so it will be a feature left to implement for the moment.  
As an alternative, put a red asterisk to show that the fields to fill in are required.  
5.When clicking on the close button in the modal message of the order form, it will direct to the home page. 

* Our store  
1.Check if, on mobile and Ipad, the image of the shop occupy all the width.   
2.Check if on Ipad pro and desktop size, the image of the shop and the image of the pastry chef including the paragraph display in two columns.  
3.Check if the google map occupies all the width on mobile.  
4.Check if, on Ipad, Ipad pro, and desktop, the google map and the details shop display in two columns.

## Lighthouse result 
* Home page 

![image](https://user-images.githubusercontent.com/76018052/111905714-5948f300-8a4d-11eb-8bf7-600ac4039a22.png)

* Patisserie page 

![image](https://user-images.githubusercontent.com/76018052/111905735-7087e080-8a4d-11eb-9001-482a7ee5134a.png)

* Viennoiserie page 

![image](https://user-images.githubusercontent.com/76018052/111905753-8b5a5500-8a4d-11eb-9037-230d2c020b22.png)

* Order online page 

![image](https://user-images.githubusercontent.com/76018052/111905773-a927ba00-8a4d-11eb-8d5e-47bd7ca54bb1.png)

* Store page 

![image](https://user-images.githubusercontent.com/76018052/111905796-c2c90180-8a4d-11eb-98e2-50fddbcde6d9.png)
