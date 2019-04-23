# Forkify
It is a simple <b>Recipe Searching</b> app

The project uses the Food2Fork API - https://www.food2fork.com/about/api.
It is limitted to use 50 queries to the API server per a day.

In order to start the project:
1. Run "npm install"
2. Run "npm run start"

When the project is running in the browser at http://localhost:8080:
1. Type, for example, <i>Pizza</i> or <i>Pasta</i> in the search field on the top of the page

2. On the left column you may see the list of all the items (per the search query).
   There are 10 items displayed per a page - the pagination functionality is activated.

3. Click on any item on the left column

4. In the middle column you may see the details per the item selected

5. Within the item details you may: 
5.1) change the quantity of servings using '-'/'+'
5.2) add the item to Favorites list clicking the 'heart' icon.
The full Favorties list is accessible on the top right corrner on the page (clicking the 'red heart' icon)
5.3) add the item to the Shopping list clicking the 'Add to shopping list' button. 
Then, on the right column you may see the item shopping details, update the quantity or remove the item from the list
