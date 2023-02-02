## <pre>                     IT 314 - Software Engineering </pre> 
### Lab 1 : Identify Functional and Non-Functional Requirements
#### Student Name : Jaimin Satani
#### Student ID: 202001202

### <pre>                  Library Information System </pre>

** 1) Functional Requirements **
      1. User should be the member of LIS, At time of issuing or returning book system should varify it.
      2. System should have Administrative privileges to some othorized persons like Librarian.
      3. System should have functionalities like borrow or return book with ease, request to extend deadline of borrowing.
      4. System should follow constraints like if booking of perticular book is done already then user should not be able to entend borrowing deadline.
      5. 
**Functional Requirements:**   
* Authentication of users at the time of issuing or returning of a book to verify if he is a member of LIS.  
* Provide Administrative Privileges to Librarian to have complete control over the system for changing the records in the system  
* System should enable users to borrow or return a book with ease and to extend the deadline of borrowing.  
* Provide separate features for users and librarian staff.   
* stem should be able to handle concurrent bookings and any possible clashes between bookings  
* Web application as a final product which should serve requests coming from students and Employees.   
* The web application should only run within the Institute LAN and should not serve any requests coming from outside of the LAN.  

**Non functional Requirements:**  
* No confidential information like passwords should be stored in plain text. They should be encrypted before storing.
* System should send reminders to the user to return the book or extend the book according to the deadline of his borrowing. 
* System should check if there is any other booking of the book before a user is extending his deadline.
* The web application of LIS should be able to handle a large number of requests and return a response within 5 seconds.
* The web application should not be down during the working hours.
* Recent HTML 5 should be used for the app.
* System should send a verification email while borrowing a book or while extending a deadline.
