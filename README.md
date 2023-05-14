# Entity_Relationship

This document is a guide on the ER diagram designed for a Library Management System, with the aim of helping to understand the structure and relationships between the different entities that make up the system.

# Objective of the Library Management System

The main objective of the library management system is to manage the lending and return of books by users, as well as the inventory control of books and the recording of relevant library information.
# Objective of the Library Management System

The main objective of the library management system is to manage the lending and return of books by users, as well as the inventory control of books and the recording of relevant library information.

# Entities
The ER diagram contains the following entities:

+ city
+ Library
+staff
+ Manager
+ Librarian
+ Reserve
+ Client
+ book
+ Exemplary
+ Author

With the information provided, the following relationships between the entities can be established:

+ The City entity has a one-to-many relationship with the Library entity, since a city can have multiple libraries, but a library belongs to only one city.
+ The Library entity has a one-to-many relationship with the Staff entity, since a library can have multiple workers, but a worker works on only one library.
+ The Library entity has a one-to-one relationship with the Library Manager entity, since a library has only one manager and a manager only works in one library.
+ The Library entity has a one-to-many relationship with the Item entity, since a library can have multiple items of a book, but an item belongs to only one library.
+ The Library entity has a one-to-many relationship with the Checkout entity, since a library can have multiple checkouts, but a checkout is made to a single library.
+ The Client entity has a one-to-many relationship with the Reservation entity, since a client can make multiple reservations, but a reservation is made by only one client.
+ The Book entity has a one-to-many relationship with the Booking entity, since a book can have multiple bookings, but a booking is for a single book.


## Parameters that this diagram meets



+ Entities
+ Attributes, primary key
+ Relations, relations with attributes.
+ Roles in recursive relations.
+ ternary relationships
+ Complex attributes. Composite attributes. Multivalued attributes.
+ Derived attributes.
+ All possible cardinalities: one-to-one, one-to-many, many-to-many.
+ Total and partial participation.
+ Weak entities.
+ Generalization-specialization. Overlapping/disjoint. Subtotal.
