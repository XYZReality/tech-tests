XYZ Reality Back-End Test
=========================

Thanks for taking the time to undertake our back-end test. There are 2 parts to the test:

1. [Design](#design)
2. [Implementation](#implementation)

Both parts are based on a schenario. Send your design/repo to your contact at XYZ Reality when you are complete.

# Scenario

Users of our cloud offering will be required to authenticate themselves. Authentication will be via username/password or a social login such as Google or Github.

Once authenticated the users will use our React SPA. The SPA will make use of a number of backend APIs. The APIs must only be accessible to authenticated users and should be resilient to token tampering.

The SPA will initially allow uses to maintain their personal information such as name, contact details and also configuration profiles for a number of custom hardware devices they have access to. This user and preference data should be saved to /read from a perisistent data store.

Users from different organizations will be using our services and so consideration should be given to multi-tenancy.

# Design

Provide a design for the [scenario](#scenario). The following should be taken into consideration:
* Service Decomposition
* Deployed to AWS
* Multi-tenancy
* Scalability to allow us to grow from 1 to 1000 customers
* Secure by design

Make sure you highlight any architecturally relevant requirements.

# Implementation

Implement a service from your design using a language of your choice (although Golang is preferred). 

This should demonstrate what you think are important engineering practices and also what makes a service *production ready*. 

> This is your opportunity to show us your skills as a software engineer. 
