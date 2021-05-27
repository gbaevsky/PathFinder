# PathFinder
PathFinder uses an algorithm to collect items in a user's cart while grocery shopping in the shortest possible path and proceeds with recommending 
users substitute items when not available at the store they are shopping from.

PathFinder gives a user the ability to either shop at one of our pre-made stores formatted through our custom JSON files, upload their own customized grocery 
cart through our specified JSON format, or build a shopping cart out of the available items throughout all our offered stores. 

By shopping at our pre-made stores, the user has the ability to select which items they would like to add to their shopping cart and more specifically
which brand of the given item out of all the options offered at that store.  After the user has selected all their items and fully built their cart, it presents 
the user with their shopping cart data such as the quantity of each item they desire, the list of items they selected, and their total pricing, 
printed out in a receipt form for them in the terminal.  Next, the shopping cart is entered into our shortest path algorithm which computes the 
shortest optimal path from the entrance of the store to each item in their cart, then back to the store exit.

Another functionality of our software is that a user can upload their own shopping cart.  We provide users with a JSON structure to upload their own shopping cart.  
After uploading the cart, the user is presented with data to help them adequately choose a store to shop at based on which items are offered at each store, 
the distance traversed to collect all the items, and comparing the overall price of buying those items at the different stores.  
If certain items they requested are not available at a store, a recommendation is made to the user for alternative items they could buy instead.

The third functionality lists all possible items from every store and allows a user to build their cart from this complete list of items. 
Again, the data above is presented to the user to help them pick the best store for their shopping needs. They can optimize for shortest price and 
shortest walking distance, and are suggested with different items when a store is missing something in their cart. 

We visualize the stores using a custom grid printer that has various symbols depending on the node type (ie. aisle, item, or open space to walk on). 
Using a variety of colors and symbols the user can clearly see the layout of the store and the shortest path to follow to collect all items in their cart.

