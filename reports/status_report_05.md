# Report sprint 07

## Your project name

planet-pals - [v7.0.0](https://github.com/nathalieclaire/planet-pals/releases/tag/v7.0.0)

## Team members of PlanetPals

* Nathalie Claire Huppert - [nathalieclaire/planet-pals](https://github.com/nathalieclaire/planet-pals)
* Estella Kinzel - [(fork) estellaaaa/planet-pals](https://github.com/estellaaaa/planet-pals)
* Tobias Bayer - [(fork) abductedRhino/planet-pals](https://github.com/abductedRhino/planet-pals)

## Tasks for this sprint
Backlog:
* (5) add products from searchview to shopping cart (app.post("/shoppingcart", shoppingcartController.addToCart);
* (3) read ShoppingCart: app.get("/shoppingcart", shoppingcartController.renderShoppingCart);
* (5) updateShoppingCart from searchview: app.put("/shoppingcart", shoppingcartController.updateShoppingCart);
* (3) delete from shopping cart in shopping cart view: app.delete("/shoppingcart", shoppingcartController.deleteFromCart);

WHAT WE'VE ALREADY IMPLEMENTED IN THE PAST SPRINTS:
*User         create(x)

Here: What the you should be able to as a user:

* Planet       read(x) -> planet is a property of product
* Product      read(x) -> /searchview
* ShoppingCart read( ) update( )
* User         read(x) update(x) delete(x) -> /register, /users

WHAT WE'RE GOING TO IMPLEMENT IN THIS SPRINT (the numbers in braces stand 
for the given fibonacci numbers from the planning poker):

* (5) update User: app.put("/profile/:email", usersController.updateUser);
* (5) delete User: app.delete("/profile/:email", usersController.deleteUser);

## The sprint backlog as a text file

```
Product Owner: Nathalie
Scrum Master: Estella

BACKLOG



IN PROGRESS
*add products from searchview to shopping cart (app.post("/shoppingcart", shoppingcartController.addToCart);
*read ShoppingCart: app.get("/shoppingcart", shoppingcartController.renderShoppingCart);
*updateShoppingCart from searchview: app.put("/shoppingcart", shoppingcartController.updateShoppingCart);
*delete from shopping cart in shopping cart view: app.delete("/shoppingcart", shoppingcartController.deleteFromCart);


DONE
* (5) update User: app.put("/profile/:email", usersController.updateUser);
* (5) delete User: app.delete("/profile/:email", usersController.deleteUser);

```

## The stories you've implemented in this sprint

```
* Branch 17: 'update User: app.put("/profile/:email", usersController.updateUser);'
* Branch 17: 'delete User: app.delete("/profile/:email", usersController.deleteUser);'

```