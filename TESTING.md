# TESTING French Pastry online shop "Un delice"

Checked the validity of the code with [HTML Markup Validation Service](https://validator.w3.org/) and [CSS Validation Service](https://jigsaw.w3.org/css-validator/) and there were no errors.

However with the code of the [order page](https://github.com/yuyu78/pastry-online-shop/blob/master/order.html), there is a warning about using the heading element h2-h6 to the sections.

![image](https://user-images.githubusercontent.com/76018052/111849799-c7d36700-890e-11eb-9b75-91531d19eac5.png)

Instead of section, the semantic div was replaced so that there is no warning.

## Testing User Stories
---
1. As a first time visitor, I want information about the French pastry so I know what is the patisserie and viennoiserie.      
1.When the visitor land to the home page, they get a brief explanation about the two types of pastries: patisserie and viennoiserie.  
2.Under theses two types of pastries, there is a button to direct to the list of product 

2. As a first time visitor, I want to view the list of pastry available so I can check the price, the allergens, the flavor.     
1.The visitor can view the list of product in the patisserie and viennoiserie page through the button "our selection" under the brief explanation in the home page.  
2.The visitor can click the link "our product" in the navbar and choose between patisserie and viennoiserie.

3. As a first time visitor, I want to easily navigate the site so I can get clear information quickly.   
1.The links of the navbar are clear with the home page, our product with two options: patisserie and viennoiserie page, order page and store page.  
2.There are clear information in the home page about the pastries, order, collection, delivery option if order online.  
3.On the footer, the contact, location and social media link.   
4.The same navbar and footer in each page so the visitor can easily navigate in different page.

4. As an interested client, I want to know the ordering process so I can receive the product.  
1.There is a link order online on the navbar.  
2.On the top of the order page, there is a requirement about the ordering process.  
3.the client can get free delivery in the first order from the home page by suscribing and enter the same email address in the form order.  
4.The visitors have to fill in their information, choose the product available and select between collection and delivery.  
5.The name of the French pastries are not obvious for every customers.   
That is why there is a link under the patisserie and viennoiserie in the order form so that if the clients don´t remember how the product look like, they can simply click on the link and will open another browser separetely in order to check again the list of product during the ordering process.

5. As an interested client, I want to know how and when I can receive my order so I can choose between collection or delivery and select a suitable time.    
1.The clients can order at store or online.  
2.If the clients order online, they can choose the two options between collection and delivery.  
In both options, the clients can select a date.

6. As a interested client, I want to get information about the shop so I can check the contact details, the location, the opening hour.    
1.The client can get information about the shop, the address with google maps, the number and opening hours, by clicking "our store" in the navbar.  
2.The client can get contact information and location in the footer. Beside the address location, there is an icon which direct to google map.

7. As a returning customer, I want to follow the shop on social media so that I can stay up to date with the latest news of the shop.  
1.The clients can find the social media link on the footer.  
2.The clients can also agree to receive marketing communication if they enter the email and suscribe in the home page, in the modal message.

## Manual Testing
---

* The Navigation all the pages:  
1.When navigating to one the theses pages: **"Home"**, **"Our product"** with the dropdown to allow to select patisserie and viennoiserie page, **"Order online"**, **"Our store"**, verify if it underlines the link of the current page.  
2.Hover over the link and check if the background changes in grey.  
3.Check if the name of the shop is clickable in direct to the home page.  
4.Check if on mobile device, the icon of the navbar collapse.

* Footer in all the pages:  
1.On Ipad, the email icon and email address were not aligned.  
To fix the issue, change the font-size of p tag in the footer to 0.9rem.  
![image](https://user-images.githubusercontent.com/76018052/111865126-80c49080-8965-11eb-94d6-87562aee5088.png)   

2.The social media icon were not displaying because in the head element, the link https://kit.fontawesome.com/47aa28a2ac.js with the kits was used and when searching on the site fontawesome, used the latest version. 
The issue was fixed when using the icon from the kits.  
3.When clicking on the social media icon and the maps in the location, check if it opens a new browser and direct to the page linked.

* Home page  
1.On mobile device, there was a little space on the right of the heroe image.  
![image](https://user-images.githubusercontent.com/76018052/111877739-edab4b00-89a4-11eb-8ccf-83c3633de0d5.png)  
To fix the issue, add in CSS in html and body element the code "overflow-x: hidden;".  
2.Verify if 