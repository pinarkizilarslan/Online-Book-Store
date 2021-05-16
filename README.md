# OnlineBookStore
Creating an online book store using object-oriented constructs

# 1.Introduction
A bookstore was created using C# form as part of the Project. The main goal of this project is to purchase three different types of products online to customers. 
It starts with a login page to access the online book store. 
The store manager has access to customers and products information and can see explanations and details about product. Customers can create an account and browse the online book store to buy from various products for sale. Within the scope of transactions, transactions are kept as reports at the click of each button.

# 2.Design
A database has been created to hold, manage and retrieve customer and product information. MsSQL was used for these processes.
The structures used and the required classes were followed at the following stages:
*	Product class is an abstract class. Since each product has a name, id and price, that is it has similar features, it has been created abstractly for the reusability of the code.
*	Product class is inherited by Book, Magazine and MusicCd classes and its functions will be overridden by the same subclasses.
*	LoginedCustomer class represents the current logged in customer. Singleton pattern is used here. The created singleton object will represent the current logged in customer.
*	Factory class uses factory pattern. Becasue they are included in the definiton of a class and produce objects by directly accessing this class. It determines the type of product according to the variety received.
*	The ShoppingCart class keep the product added to the hopping cart, the shopper, the amount of the payment to be made.
*	Network class carries out the control of internet access, sending mail and checking mail.
*	Base64 class allows class photos to be stored and captured. 
The application was shown on the computer with an icon on the bottom right of the task bar.
The shopping invoice has been sent to e-mail addresses. 


### Team Members
* [Pınar Kızılarslan](https://github.com/pinarkizilarslan)
* [Damla Dalgıç](https://github.com/damladlg)
* [Ayşe Kaya](https://github.com/ayseekaya)
* Sezer Demir Dedek
