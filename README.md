Project 1:
For this project I decided to create a web API that stores contact information. Create, read, update, and delete operations can be done through a browser. Contacts are assigned an ID which is used to identify them within the database and drive the API CRUD operations. The database information, including any CRUD operations, are saved to a database which the developer can specify. The database integration uses the Entity Framework, while the ASP.NET 6.0 provides the front end of this web API. 


The ContactsController.CS file contains the following Http functions which are used in the API (can be interacted with via a browser):

[HttpGet] – GetContacts()  – Returns all stored contacts. 

[HttpGet] – GetContact() – Returns a single contact based on the contact’s id (provided by user). 

[HttpPost] – AddContact()  – Adds a contact. All fields must be provided by user.  

[HttpPut] – UpdateContact()  – Updates a contact. All fields must be provided by user.  

[HttpDelete] – DeleteContact()  – Deletes a contact that user specifies by id.   




Features:

Full CRUD operations - Create, Read, Update & Delete entries, using ID system. 

Uses project template for creating an ASP.NET core application with an example Controller for a RESTful HTTP service. Template is also used for ASP.NET Core MVC Views and Controllers.

USES .NET 6.0 (long term support)

Entity Framework

SQL Database migration + integration – Database can be changed. 
