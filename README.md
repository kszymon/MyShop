### Projekt MyShop 

The MyShop project is a simple store written in Java, using technologies such as CSS, HTML and Thymeleaf. It focuses on the basic elements of the store and the interactions between them.

## Models

### Item

The `Item` class represents a product in the store. Contains fields such as:
- `id`: unique product identifier
- `name`: product name
- `price`: product price
- `imgUrl`: image URL

### OrderItem

The `OrderItem` class describes the product in the order. Contains fields:
- `ordereId`: unique identifier of the order item
- `itemId`: product reference
- `amound `: order amount

### Order

The `Order` class stores order data. Contains fields such as:
- `orderId`: unique identifier of the order
- `firstName`: name of the ordering person
- `lastName`: name of the ordering person
- `address`: address of the ordering person
- `postCode`: postal code
- `city`: city
- `created`: date and time of order creation

## Pages available to the user:
1. Home page: Here users can browse available products in the store. This is a place where you can view a list of products, their names, prices and descriptions.
2. 'Cart' tab: This is where users can see the products they have added to their cart. You can view the list of products in your cart and their total price.
3. 'Order' tab: After clicking the "Order" button, users go to the tab where they can provide their order details. Here you can collect information such as the customer's name, delivery address, etc.


## Starting the project

1. Clone the repository.
2. Install the required dependencies.
3. Run the application.

Thank you for your interest in the MyShop project!
