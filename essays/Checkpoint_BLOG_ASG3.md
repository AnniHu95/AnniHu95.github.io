---
layout: essay
type: essay
title: "Checkpoint BLOG Assigment3"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - essay
---
1.	Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.
2.	Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.
I will use session cookies to store the information of the users, and the products they selected to purchase from the products pages.
"{
"OUTER":[
  {
    "name": "Z-line",
    "price": 23.00,
    "image": "images/Z-line.JPG",
    "quantity_available": 150
  },]
…
}"
This is an example of my code, and I am using an array to display my products.
3.	How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
For security purpose, my invoice button will not show up in the pages before log in page, and I used “if” statements to protect the page.
4.	Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)
For security purpose some of the buttons will not show at a certain point, and the client will be automatically logged out after a long period of time not making any actions.
5.	If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
I am not working with partners.
6.	How are you approaching Assignment 3 differently than Assignment 2?
I think will make it more detailed, as my store is about selling clothes, so if I could add the sizes for the products, it would be more reasonable.
7.	A link for my BLOG: [[https://youtu.be/J92P_bJc4KA](https://youtu.be/phYTf7PqcmM)](https://youtu.be/phYTf7PqcmM)

