# GuestHouseApp

## Introduction
A guesthouse booking web application created using .NET
The Web application was created as a part of my internship at Birla Cellulosic.

It comes with the following features:

a. When the user goes to the web site, the user is asked for username and password.

b. On successful login, the user is redirected to a personalised user page, where he has two options:

  * To apply for guesthouse or meals
  * To see the history of his applications
  
c. When the user applies for the guest house or meals, the application automatically assigns the application an application number and then send the application to the department head of the user. If accepted the application goes to the functional head of the user and if accepted there too, it goes to the Head Of Human Resources for final verification. If accepted there, a database in the server is updated and user is given a mail saying his application is accepted. The same is reflected in the user report profile too.

  * But if the application is rejected at any process, a mail goes to the user saying that the application was rejected and changes are done in the web srever database too.
 
  * Sometimes it is poosible that a particular authority is absent. That`s why, a dedicated admin page has been built which can view all the applications and can choose to accept or reject them.

## Dependencies
The following applications need to be installed in the system:

* .NET
* Microsft Visual Studio, Version>=2017
* IIS
