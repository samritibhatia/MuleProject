# MuleProject
Creating Mule Project
# Project Title

This project gives the customer data to the end users by consuming the Restful API using RAML.  

## Getting Started

1) Import the project in to Anypoint Studio.
2) Run the project as a MuleApplication.
3) Test using Postman(being used for testing of API) .

### Prerequisites

1)Install Anypoint Studio6.3.0 with embedded MuleRuntime3.8.
2)Install Postman in chrome browser.

## Running the tests

1)List of Customers: Use "localhost: {PORT}/api/listOfCustomers"  in postman to get listOfCustomers present in the database

2)Single Customer On basis of ID(Unique ID): Use "localhost:{PORT}/api/getCustomerByID{ID}"  in postman to get single customer .ID is dynamic . You can add value.

3)Get Customer On the basis of Query Parameter: Use "localhost:8081/api/getCustomerByQueryParam"  in Postman  and add QueryParameters like FName,LAME,ADDRESS. If no queryParameter is added then list of customers will be displayed by default.



## Author

Samriti Bhatia
