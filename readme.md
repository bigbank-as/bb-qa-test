# Getting Started
This is a dummy application against which you are to create a REST test application.


## Assignment 1
In our every day development process we are using docker. Quality Engineer who is also writing code should be able to use the same tools as developers. At least in their very basic form. Your first assignment will be running the application in the docker container. Only then you can start with next step of this test task (you need to run the service against which you want to create tests).
* With this assignment you are demonstrating your capability to work independently

#### Running the application in docker
``
docker-compose up
``

When the application is running you can view its endpoints
* http://localhost:8080/swagger-ui.html

When accessing the Swagger endpoint, you will find ``customer-controller``. That will be your implementation target.

## Assignment 2
***You are given a Jira user story with following contents.***

**IN ORDER TO** provide Loan Application team the ability to create and retrieve customers

**AS A PRODUCT MANAGER** I want to have a Customer Service

**IN ORDER TO** be able to create new customers

***Acceptance criteria***
* Can create new customers via REST
* Can retrieve existing customers via REST
* Customer has an email, first name and a last name
* Our first five customers from csv are migrated to the database

*In the middle of the sprint PM has told you and devs that with this new exciting Customer Service, business found out they also must be compliant with regulations from the state. Regulations state that all customers must give agreement for marketing e-mails. Hence marketing consent must also be available for customer that can be modified whenever necessary*



### Assignment 3
**Your manager asks in the end of the day:** "*Tomorrow is the release for Customer Service, is everything ok from your side?*"

What do you reply?

# How to formulate your solution
### What to do
* Create release tests for most business critical part(s) of ``Customer Service`` application
* Use Java8 (or above), testNG and Rest Assured
* Document all the bugs you've found

##### Bonus points (If you want to impress us)
* Not creating base classes
* Dependency injection with Guice or testNG
* DDL of the sqlite database concerning customer data

### Where to put your solution 
* Commit your code and comments to github
* ___Do not___ include this __readme__ or __any other files__ from this repository in your solution
