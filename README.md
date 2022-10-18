# Moonshiner Product Scanner

# Project description
Application developed in order to make easier for customers to scann and add products to the cart.
With the help of https://serratus.github.io/quaggaJS/ the mobile/laptop/pc cam can recognize and scann
a bar code and fetch its value

# User Instructions
Access 
https://aciliocarraro.github.io
Add the user name that must be longers than 2 characters and click Login.
The id will be automatically generated.
In "Scanner", by pressing the "Start" button, it will activate the cam. You may have to give it permission.
The "Start" button will automatically change to "Stop" giving you the chance to stop the cam.
Point the cam focus to a barcode and apreciate how fast the application recognizes it.
A new form will be enabled giving you the chance to change the products name. Enter a new name and click
"Save product name" or just accept the given name by clicking the button.
In "Basket" you will be able to visualise the products that were added to the cart and change their quantities. Be aware that if you click the "-" and the quantity is already 1, it will remove the product
from the cart. Both buttons "+" pr "-" will change the "Total items" and "Total price" of the cart.
Once you are happy with the products and their quantities, click on the "Checkout" out button.
It will clear you cart and send the purchase to the database.
By accessing the api below, give the user_id and the items can be seen online:
https://acilio.codefactory.live/moon_basket/display_all.php?id=user_id


# Dev Instructions
If any changes were made to this repo, make sure to run the commands below:
npm run build
npm run deploy
The github branch gh-pages will be updated and so the website.

# Components
Basket
    Basket
    MinusBtn
    PlusBtn
Head
Landing
Logo
Scanner


# Credits
Qhagga barcode scanner library:
https://serratus.github.io/quaggaJS/

