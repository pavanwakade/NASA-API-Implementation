***What is the purpose of the Nasa API Implementation project, and what features does it provide?***

- This project is a full-stack web application that integrates with NASA's APIs to provide users with two main features:

*Astronomy Picture of the Day (APOD):* Users can view NASA's daily astronomy picture along with its description and details.
*Mars Rover Photos:* Users can explore photos taken by Mars rovers  based on specific dates and cameras.

- *Home Page:* Introduction to the project.
- *APOD Page:* Displays the Astronomy Picture of the Day.
- *Mars Rover Page:* Allows users to filter and view Mars rover photos.
- *Admin Page:* Enables CRUD operations for APOD entries.


*Backend:*

Developed using Spring frameworks for scalability and maintainability.

Implements RESTful APIs for fetching and managing data by using RestTemplate.

For database we use MySQL database for storing APOD entries.

Security:
we Spring Security for role-based access control.
Supports JWT authentication for API endpoints.
Custom login pages and restricted access for admin functionalities.
