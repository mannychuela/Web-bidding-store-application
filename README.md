# Web online store applicaton

Mini eBay

+ Description:
    Implement a bid-based online store.

+ Requirements:
   The web application based on JAVA has the following capabilities:

    1. User accounts including sign up and login.

    2. The products classified by departments (e.g., Electronics, computers, books).

    3. The user is able to sell a product classified by department. When registering the product, the user can include a product name, a description, a starting bid value, a picture, and a due date.

    4. The system provides a search box with the capability of refining the search based on the department. However, the default search is executed on the entire product database.

    5. The search results are listed with the product description (Name, department, and current bid) and a picture.

    6. Once the user selects a product, the system presents a new page with the complete product description including a bigger picture.

    7. Once the user intends to make a bid for a product, it is required to be logged into the system. The user can enter the bid value, and the system shows the highest bid for the product.

    8. The system provides an administrator role with the ability to add, modify, and remove users, products, and departments.

 + Key things about this project

    1. The web pages does not include the database connection string, nor the database query strings. The access to the database is encapsulated in Java classes.
    
    2. Each page validates the user permission.
    
    3. Database does not have a table with the user’s plain-text password. The project implements Hashing.
