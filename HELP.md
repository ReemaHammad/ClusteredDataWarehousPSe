# Getting Started


### Application Logic - User Guide
This document provides instructions on how to use the application to process requests and import data into the database.

#### Application Logic
application to add Fx deals and presist them into the database, by using a restfull api to handle adding deals with specific validations

#### Database
The system  uses mysql database.

#### Validation
The system validations for each add deal request, such as:

1- Ensuring that all required fields are present.
2- Validating field data types and formats, through data-types.
3- Ensuring unique requests only for deals, and that is  detected based on their unique identifier (Deal Unique Id).

#### Project Structure
The project should follow the structure of a Maven project, including proper package organization and dependency management.

#### Error Handling
The system provides error handling, with clear error messages in DealService to handle user exceptions.

#### Logging
logs are provided in DealService to log user data for tracing issues when dealing with the add request.

####  Unit Testing
unit testing using junit and mockito for mocking test data, for the business logic in DealService.

