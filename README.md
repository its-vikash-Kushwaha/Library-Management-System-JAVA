# 📚 Library Management System -Java





A Library Management System made using the concepts of Object Oriented Analysis and Design. Minimal Code is written in the GUI and the entities are decoupled as well. The interface is console based. This project was designed during the course "Object Oriented Analysis and Design CS309".

The **Class Diagram** of the project is also provided along with the **Database Schema** file. The class diagram file can be opened using [Star UML](http://staruml.io/).

## Class Diagram
![class diagram](../master/images/diagram.PNG)

**Note**: After Refactoring, new Class "HoldRequestOperations" is added to the above structure which lies in between the HoldRequest class and Book class.
This class removes the bidirectional dependency between HoldRequest and Book. More details mentioned [here](https://github.com/OSSpk/Library-Management-System-JAVA/issues/9) 

## Interface
<p align="middle">
   <img src="../master/images/interface.PNG" width="400"/>
   <img src="../master/images/interface2.PNG" width="400"/>
</p>   

## Actors:
The actors include the following: 
* Librarian
* Checkout Clerk
* Borrower
* Administrator

## Use Cases:
After determining the actors, the second step in use case analysis is to determine the tasks that each actor will need to do with the system. Each task is called a use case because it represents one particular way the system will be used.

**In other words, only those use cases are listed that actors will need to do when they are using the system to solve the customer’s problem.** 

### Borrower:
* ❏ Search for items by title.
* ❏ ... by author.
* ❏ ... by subject.
* ❏ Place a book on hold if it is on loan to somebody else.
* ❏ Check  the  borrower’s  personal  information  and  list  of  books  currently
borrowed.

### Checkout Clerk:
* ❏ All the Borrower use cases, plus
* ❏ Check out an item for a borrower.
* ❏ Check in an item that has been returned.
* ❏ Renew an item.
* ❏ Record that a fine has been paid.
* ❏ Add a new borrower.
* ❏ Update a borrower’s personal information (address, telephone number etc.).

### Librarian:
* ❏ All of the Borrower and Checkout Clerk use cases, plus
* ❏ Add a new item to the collection.
* ❏ Delete an item from the collection.
* ❏ Change the information the system has recorded about an item.

### Administrator:
* ❏ Add Clerk.
* ❏ Add Librarian.
* ❏ View Issued Books History.
* ❏ View All Books in Library.


## How to Run
1- Install these:
 * [Java SE Development Kit 8 (JDK 8)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
 * After installing JDK 8, install [NetBeans IDE](https://netbeans.org/downloads/)

2- Open NetBeans IDE. Click on File -> Open Project and browse to the downloaded folder named "Project" and select it. It will load the NetBeans project.

3- Now everything is setup except the Java DB (Derby) Database of NetBeans. So, follow these steps to setup the database:

**Step 1:** In the Netbeans Window, there is a tab named "Services" on the left. Select it. Then right click on JavaDB > Properties and    change database location to "Database" folder downloaded with this repository (its placed besides the "Project" folder).

![step1](../master/images/step1.PNG)
   
**Step 2:** After that a database named LMS will show up under JavaDB tab. Now Right Click Databases > New Connection and select Java DB Network and click Next. 

![step2](../master/images/step2.PNG)
   
**Step 3:** Provide the following database crendentials in the next popup and click Next.
  ```
  Host: localhost
  Port: 1527
  Database: LMS
  User Name: haris
  Password: 123
  ``` 
![step3](../master/images/step3.PNG)

**Step 4:**
Now just click Next for the rest of the windows. After all this the database connection is made. Make sure that you connect with the database before running the project by right clicking on the connection and selecting connect. Now you are ready to run the project!

![final](../master/images/final.png)

## Note
The password for Administrative Functions is *lib*. The admin adds new clerks and librarian, then they both do the rest of the functions.

<hr>

## Authors 👋

You can get in touch with us on our LinkedIn Profiles:

#### 

[![LinkedIn Link](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=linkedin&longCache=true&style=social&label=Follow)](https://www.linkedin.com/in/harismuneer)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/harismuneer)

#### M

[![LinkedIn Link](https://img.shields.io/badge/Connect-maham--amjad-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/maham-amjad-40796b177/)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-maham--amjad-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/MahamAmjad)

If you liked the repo then kindly support it by giving it a star ⭐ and share in your circles so more people can benefit from the effort.

## Contributions Welcome
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Library-Management-System-JAVA.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Library-Management-System-JAVA/issues)

If you find any bugs, have suggestions, or face issues:

- Open an Issue in the Issues Tab to discuss them.
- Submit a Pull Request to propose fixes or improvements.
- Review Pull Requests from other contributors to help maintain the project's quality and progress.

This project thrives on community collaboration! Members are encouraged to take the initiative, support one another, and actively engage in all aspects of the project. Whether it’s debugging, fixing issues, or brainstorming new ideas, your contributions are what keep this project moving forward.

With modern AI tools like ChatGPT, solving challenges and contributing effectively is easier than ever. Let’s work together to make this project the best it can be! 🚀

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](../master/LICENSE)

Copyright (c) 2018-present, vikashKushwaha

<!-- PROFILE_INTRO_START -->






<!-- PROFILE_INTRO_END -->





