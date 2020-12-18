# GroceryPicker
This repository is for grocery shopping automation - create csv file from a cart, import csv file to fill cart

It currently only works on Morrisons and Sainsburys website. 

cartToCSV.js is a script to create a csv file from the cart. 
To use it: 
1. Load the script via any Chrome Javascript Injector, such as https://chrome.google.com/webstore/detail/scripty-javascript-inject/milkbiaeapddfnpenedfgbfdacpbcbam.
2. Run the script when you have some items in your cart.

index.html is a web form where you can upload the csv of shopping item and convert it into a html table. It works with addToCart.js to add items to your shopping cart. 

addToCart.js is a script to add items to the cart.
To use it:
1. Load the script via any Chrome Javascript Injector, such as https://chrome.google.com/webstore/detail/scripty-javascript-inject/milkbiaeapddfnpenedfgbfdacpbcbam.
2. Set it to run automatically on page load.
3. Open index.html and upload the csv file in the sample format.

To do:
* Use jQuery in addToCart.js
* Add support for ASDA
* Build a Chrome extension
* Add support for Tesco
* Add support for Other supermarket