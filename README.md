# e-Stage
Bac3 Advanced Web Project

# Presentation
## Description of the application
  The application called «e-Stage» is an online platform (in web format) for students and companies wishing to follow or offer internships. \
  On this platform it will be possible to create an account, see/create training offers, communicate by messages to the subjects of online offers, book interviews….\
  This platform will allow both stakeholders to structure and gather interactions related to internship offers, on a single website. 
#  Details
##  Technical Constraints
###  Front-End
  The user interface will be created using the **Framework React** with **Typescript** respecting a *MVC structure*
We will distinguish 2 types of presentation of the page depending on whether we are connected as a client (internship researcher) or a company (internship advertiser)
###  Back-End
  The web service will be developed in Java using the **Framework Spring Boot**. The structure must strictly respect **the hexagonal architecture**.
For the main database, it will be in **MySQL** format. The real-time database of the messaging service will be made using **Firebase**. These 2 databases will communicate with the service using a secure API.
##  Features
###  Common Features
-  Creation of an account (via web form)
-  Search internship offers (+ filtering with tag system)
-  Live chat via messaging
-  Notification system
-  Change personal account details
-  Calendar of recorded interviews
-  Retrieve a history 
-  Register for an internship offer
-  Upload your CV (PDF format) to your profile
-  Create an internship offer
-  Select applicants 

##  SCRUMB
  It will not be detailed when the database, should it be implemented, or other services or details too precise, the freedom is left to the good sense of the developers. 
The order of trivial priorities is as follows:
1.  Common Functionality
2.  Client & Enterprise
   
The suggested detailed chronological order of development is as follows:
1.  Account Creation and Login
2.  Modification of Personal Data
3.  Create a web form for registration and login
4.  Creation of internship offer
5.  Registration for Internship
6.  Search for an internship (filter system may be implemented later depending on project progress)
7.  Upload CV to PDF
8.  Create/Retrieve History
9.  Select Applicants
10.  Notification and Email
11.  Live Chat
12.  Schedule
    
**NOTE:**
-  Features 1 -> 5, are **essential** in order to have the minimum required for a semblance of functional application.
-  The orders of the other features are globally Invertible, this list is only a suggestion. It is also possible that some of these features are not developed according to the deadlines to be respected.
