
**Installing Stencil CLI**
	- npm install -g @bigcommerce/stencil-cli
	- Docs:  https://developer.bigcommerce.com/stencil-docs/installing-stencil-cli/live-previewing-a-theme
	- use bigCommerce cornerstone theme


**Params:**
	- Create a product named Special Item** 
		- Category: 
			- Special Items
		- 2 images for display
		- Behavior:
			- Only item which shows in this category
			- show products second image when hovered over

**Category Page:** 
		- Button on top called Add all to Cart:
			- click adds item to cart
			- user is notified that cart has item in it
			- if customer is logged in: 
				- have banner with customer info (name, date,age,etc/):
					- update data with handlebars

**Cart**
	- If cart has item, show button next to Add all to Cart button called Remove all items
	- Both buttons should utilize the Storefront API for completion


# Use branches on github and merge prs 

**Build Steps**
	1) mkdirs and install stencil CLI
	2) sign up for store
	3) create store using bigCommerce cornerstone theme
	4) init git and add repo
	5) Build product
	6) Build buttons
	7) add customer info
	8) README: 
		- follow template
		- include preview code and URL for store



You are here: 
	- Button is made for categories
	- Hover event is happening on image, but new image is not loading
	- Need to hook up button still
	



**Prompt:


Setup  
----------  
Sign up for a BigCommerce trial store, this will be valid for 15 days and will be needed to complete the test  
Install Stencil CLI for local development, you will be using the default Cornerstone Theme that comes standard with new BigCommerce stores  
  
* Refer to the BigCommerce developer documentation for any questions you might have. It will contain all the info needed to complete the tasks below  
  
  
Task  
----------  
Create a product called Special Item which will be assigned to a new category called Special Items. Be sure to add at least 2 images during the product creation  
  
The Special Item should be the only item which shows in this category - create a feature that will show the product's second image when it is hovered on.  
Add a button at the top of the category page labeled Add All To Cart. When clicked, the product will be added to the cart. Notify the user that the product has been added.  
If the cart has an item in it - show a button next to the Add All To Cart button which says Remove All Items. When clicked it should clear the cart and notify the user.  
Both buttons should utilize the Storefront API for completion.  
  
Bonus  
----------  
If a customer is logged in - at the top of the category page show a banner that shows some customer details (i.e. name, email, phone, etc). This should utilize the data that is rendered via Handlebars on the Customer Object.  
  
Submission  
--------------------  
Create a GitHub repo for your codebase . In the Readme file remove the current data and add your own which describes a brief overview of your test.  
Be sure you include the Preview Code for the Bigcommerce Store, along with its URL, so we can view it. Then reply to this email with the Github repo link.