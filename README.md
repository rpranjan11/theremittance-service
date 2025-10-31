 
### Installation
In order to run/execute/deploy this project, the following software/tools/packages need to be installed:
* Java version >= 17 [I used version 21]
* Eclipse IDE - Latest version [preferred]

### Project setup in Eclipse IDE
* Install Buildship Gradle Integration from the Eclipse marketplace
* Import the project into Eclipse as a Gradle project
* Set the appropriate project properties like Java version [if multiple versions are installed on the pc]
* Right-click on Project from Project Explorer and Select Gradle>Refresh Gradle Project
* Now, the project can be Gradle Build and Gradle Run


### Implementation/Development Details
All the Assignment constraints and guidelines have been fulfilled as per my best understanding to them.
* The project is properly structured into standard layers that the SpringBoot project follows
* All 5 APIs are implemented as per the document provided, and follow the specific API constraints provided in the document
* H2 Database is used, which can be accessed on http://localhost:8080/h2-console after running the app
* Only JSON has been used as Request and Response
* Authentication Token is implemented for the verification of API requests
* A logger is implemented for tracking the logs of code execution
* Error and Exception management is used at a high level due to less information being provided about it
* Used Utility classes to separate the Utility functionality from the service/business logics
* JUnit Test cases are implemented for all the APIs in the test package
* There can still be a scope of code cleaning, implementing any missed logic, introducing inner layers, proper error and exception management, unique Authentication & Authorization process, etc., to make the project production-level. Due to time constraint, I have focused to fulfill the most necessary constraints and deliver the assignment.


### Also, I have uploaded a video in the same drive folder of the project running in my PC. The video contains calling APIs from Postman and verifying execution from logs and API responses, checking success, invalid, and error scenarios of APIs.

