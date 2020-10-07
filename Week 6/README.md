# week6
Dynamic images

Add an "image" key to your enemy objects
Add an <img> on your page for the enemy
When a random enemy is selected, update the image on the page
 

Loot Chance

Create a file named 'items.html'
Make a variable in that file called "items" and set it to an array of objects
Each object should have a "name" key and a "chance" key, just like we did in class
Write a function that generates a random number, loops through all of the items and picks an item at random from those items that have a higher "chance"
If your items are all buffs (i.e. potions or damage modifiers) you can adjust the user object directly by adding hp or attack
Or you may add an "inventory" array on the user object to hold the loot (dont worry about using it yet in that case)
When an enemy is defeated, call this new function to determine if  the enemy dropped anything for you
 

Output Message

Create a div on the page with the id of "output"
Style it pretty
Create a function that accepts a message and prepends the message, wrapped in a <p>, to the output div 
When an enemy is defeated, 
