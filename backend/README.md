XYZ Reality Back-End Test
=========================

Thanks for taking the time to undertake our back-end test. There are 2 parts to the test:

1. [Design](#design)
2. [Implementation](#implementation)

Both parts are based on a schenario. Send your design/repo to your contact at XYZ Reality when you are complete.

# Scenario

Users of our cloud offering will be required to signup and then when logging in they are required to authenticate themselves. Authentication will be via username/password.
When signing up the user will be able sign up with the details:
1)  Unique Email address
2)  First and Surname
3)  Company
4)  Address
5)  Telephone Number
6)  Password

Once authenticated the users will use restful interface. The front-end will make use of a number of backend APIs. The APIs must only be accessible to authenticated users and should be resilient to token tampering.

The front-end will initially allow uses to maintain their personal information such as name, contact details and also add configuration profiles for a number of custom hardware devices they have access to. 

Configuration Profile Fields:
1)  Device ID
2)  RotationX
3)  RotationY
4)  ShiftX
5)  ShiftY

Additionally the front-end will be used to manage a list of tasks assigned to a user to complete. This user, preference and task data should be saved to /read from a perisistent data store.
Task List Details:
1) Task ID
2) Task Name
3) Task Description
4) Task Date Assigned
5) Task Due Date

Users from different organizations will be using our services and so consideration should be given to multi-tenancy. 

# Design

Provide a design for the [scenario](#scenario). The following should be taken into consideration:
* Service Decomposition
* Deployed to ideally Google Cloud (if short on time then to AWS)
* Multi-tenancy
* Scalability to allow us to grow from 1 to 1000 customers
* Secure by design
* APIs will evolve over time, how can we accomodate different clients using different API versions
*  Additional task is to deploy to Google using Terraform.
*Consideration should be given to provide all the information for a front end developer to hook up to the end points

Make sure you highlight any architecturally relevant requirements.


# Implementation

Implement a service from your design using ideally <u><b>Golang</b></u> or a language of your choice). 

This should demonstrate what you think are important engineering practices and also what makes a service *production ready*. 

> This is your opportunity to show us your skills as a software engineer. 
