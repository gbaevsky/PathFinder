# PathFinder
PathFinder uses an algorithm to collect items in a user's cart in the shortest possible path while grocery shopping and proceeds with recommending a user 
substitute items when not available at the store they are shopping from.

PathFinder gives users the ability to either shop at one of our pre-made stores formatted through our custom JSON files, upload their own personal grocery 
cart through our specified JSON format, or build a shopping cart out of all available items.

By shopping at our pre-made stores, users can select which items they would like to add to their shopping cart and more specifically which brand of the 
given item out of all the options offered at that store.  After users fully build their carts, it presents them with their shopping cart data such as the 
quantity of each item they desire, the list of items they selected, and their total pricing, printed out in a receipt form in the terminal.  Next, the 
shopping cart is entered into the shortest path algorithm which computes the shortest optimal path from the entrance of the store to each item in their cart, 
then back to the store exit.

Another functionality of the software is that users can upload their own shopping cart, using a JSON structure provided for them. After uploading their cart, 
the users are presented with data to help them adequately choose a store to shop at based on the items that are offered at each 
store, the distance traversed to collect all the items, and comparing the overall price of buying those items at the different stores.  
If certain items they requested are not available at a store, a recommendation is made to the user for alternative items they could buy instead.

The third functionality lists all possible items from every store and allows users to build their carts from this complete list.
Again users can optimize for lowest price and shortest walking distance, and are suggested with different items when a store is missing something in their cart. 

We visualize the stores using a custom grid printer that has various symbols depending on the node type (ie. aisle, item, or open space to walk on). 
Using a variety of colors and symbols the user can clearly see the layout of the store and the shortest path to follow to collect all items in their cart.

