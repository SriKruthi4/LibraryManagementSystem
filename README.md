# LibraryManagementSystem
The implemented library management system functions as a comprehensive tool designed to streamline various library processes through the integration of technological tools, thereby enhancing efficiency and productivity. The system facilitates user registration, simplifies book searches using multiple keywords, and grants users the capability to borrow books. It is noteworthy that the system imposes specific restrictions, allowing individuals to borrow a maximum of three books at a time. Additionally, a fine system is incorporated, automatically imposing fines and generating bills for users with overdue books.

System Components

The library management system we intend to develop is made up of multiple integrated components that have their own individual functionality as well as work together with the other components to form a fully integrated system. Even through the development process we have developed the components one by one, ensuring they are robust and bug free and integrated them together, to form the system. Some of these components are interactive with the user, such as authentication and book checkout, while there are some that do not allow the user to interact with them, but are crucial for the functioning of the application. 

The library management system has the following components. 

1. Library Search : Library Search is the next module that users get to when they login to the application, using this they can search the library database to find any book they need. The searches can be done using book names, author names or ISBN numbers. It provides all the matching results to the users based on their query. 

2. Book Checkout : This module works towards allowing users to checkout books online. Once a user searches for a book and finds it, this module comes into action and using this the users can checkout books, thereby adding this book to their checkout profile. 

3. Fines Module : Fines module is also a crucial module of the system. While the user does not directly interact with this component, it fuels the successful running of an integral system. This feature checks the user's profile to see whether they have any pending books and if they do have any, it adds a fine of a specific amount to their profile. Based on this fine, when the user checks out the next book or when they are returning it, they will be asked to pay the fine or will not be allowed to check out any books from the library. 

