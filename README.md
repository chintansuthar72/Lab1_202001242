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


# **<pre>Mobile application to aid hear loss</pre>**

## 2) Identify scope, features and non-functional aspects of the following problem

### **Scope**

1. The 5% of people worldwide who have hearing loss will be the application's target market.
2. Such individuals would be the intended audience for this software since they are the ones for whom it was created.
    
### **Features**

1. The application will run in the background also.
2. The application will alert user about incoming sounds.
3. The sound recorded must also be logged properly in readable format
4. The application will alert the user when it recognizes the sounds of critical situations.
5. Notify friends and relatives if a critical emergency is identified and the user doesn't respond.
6. Latency of application must be much less (2 ms around).

### **Non-Functional aspects**

1. The application should alert the user through some vibrations or something else.
2. When walking, the application should be able to recommend the lanes with the least amount of traffic.
3. Users should be able to send their current position to friends and relatives in case of an emergency via the app.
4. Users should be able to add extra sounds, which the application must be able to identify the user.
5. The latency of the app should be at most 2 seconds.