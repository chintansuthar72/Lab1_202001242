# Lab1_202001242

# <pre>IT 314 - Software Engineering </pre> 
## Lab 1 : Identify Functional and Non-Functional Requirements
## Name : Chintankumar Suthar
## ID: 202001242

# **<pre>Library Information system   </pre>**

## 1) Identify Functinoal and Non functional Requirements

### **Functional Requirements**

1. Login functinality of different roles of user
    - Admin role
    - Staff or Employee role
    - Student or Normal user role
2. Role wise different functionalities
    * Admin role
        - can add new book/s
        - can remove current book/s
        - can edit information of user of Staff role
        - will have all administrative privileges
    * Staff role
        - can check for particular book is available for issue or not
        - get list of all books which are issued
        - get list of all books which are not issued
        - get list of all books which are issued and return period is over but yet not returned by user
        - get unique id or code for particular book
        - can edit information of user of Student role
    * Student role
        - issue a book
        - return a book
        - reissue a book
        - search the particular book is available or not
3. Authentication required for all roles to do particular action or to use particular functionality of that particular role.
4. User can freely browse books without any login or authentication.
5. Remainder should go on student's email id before one day of returning of book.
6. Verification mail should go on student's email id at the time of issuing and returning of book.
7. Efficient searching functinality for particular book should be there on platform.
8. Platform should be as web application and should handle parallel requests. Web application should accept requests from inside campus only. 
    
### Non-Functional Requirements

1. Privacy
    * Each user's privacy should be maintained and platform should not leak any confidential information.
    * Confidential information like password must be encrypted before storing in database.
2. Reliability
    * Database should be persistent, consistent, durable and should give accurate information only.
3. Scalability
    * Platfrom should be able to handle large number of requests or load and latency should be much less.
    * Platfrom should be auto scalable based on number of users.
4. Compatibility
    * Latest web technologies should be used in making web application.
    * Web application should run on older versions of web browser also and on different devices also.
5. Maintainability 
    * Web application's should be written in very well and easily understandable manner so that maintainance of application can be easy.
6. Usability
    * User interface of web application should be clean and simple to use for each type of user.

