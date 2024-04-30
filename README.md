# University_food_Ordering_System
Introduction:
This report provides an overview of the model classes implemented in the University Food Ordering System, a JavaFX application designed to facilitate food ordering within a university campus. The model classes are essential components of the system, responsible for representing entities such as users, orders, products, and delivery information.

Administrator Class:

The Administrator class extends the User class and represents administrative users of the system.
It includes attributes such as username, password, name, and the username of the user who added the administrator.
The class provides a toString() method to convert the object to a string for display purposes.

VendorOrderView Class:

The VendorOrderView class represents the view of vendor orders within the system.
It includes attributes such as order ID, product ID, quantity, vendor ID, customer name, and order status.
The class calculates the total price of the order based on the unit price of the product and the quantity ordered.
It retrieves additional information about the product from a file ("Products.txt") and sets the stock quantity, product name, and unit price accordingly.

DeliveryOrderView Class:

The DeliveryOrderView class represents the view of delivery orders within the system.
It includes attributes such as order ID, quantity, product ID, shop name, customer ID, customer name, customer address, order status, and total price.
The class retrieves information about orders from a file ("Orders.txt") and fetches additional details about products and customers from corresponding files ("Products.txt" and "Customers.txt").
It sets the product name, shop name, customer name, and customer address based on the retrieved information.

Conclusion:
The model classes described above play a crucial role in the functionality of the University Food Ordering System. They encapsulate data and behavior related to different entities within the system, facilitating efficient data management and manipulation. The classes adhere to principles of encapsulation and abstraction, contributing to the maintainability and scalability of the application. Further enhancements and refinements can be made to these classes to improve the overall functionality and user experience of the system.





