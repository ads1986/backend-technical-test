# Addison Global Backend Technical Assesement

## Overview

This repository contains my submission for the Technical Assessment as part of the Backend Developer role at Addison Global. 

The assessment aims to evaluate my backend development skills, problem-solving abilities, and understanding of best practices 
in creating robust and scalable applications. 

This project was built following the [Backend Technical Assessment](https://github.com/ads1986/backend-technical-test/blob/master/README.md).

## Project Structure

The project is organized as follows:

    ├── src
    │ ├── app.py # Main application file
    │ ├── database.py # Database configuration and operations
    │ ├── models.py # Data models and schemas
    │ ├── tests.py # Unit tests for the application
    │ └── utils.py # Utility functions
    ├── requirements.txt # Python dependencies
    ├── README.md # Project documentation (you are here!)
    └── .gitignore # Git ignore rules

## Installation

1. Clone this repository to your local machine.
2. Ensure you have _Java 17_ or ***higher version*** installed.
3. Install the project dependencies using the following command:

## Usage

To run the application, execute the following command:

```bash
$ ./mvnw spring-boot:run
```
The application will start on `http://localhost:8000`.

## API Documentation

The application exposes the following endpoints:

* `/api/resource`: [Description of the endpoint and its purpose]
* `/api/resource/{id}`: [Description of the endpoint and its purpose]

For detailed API documentation and usage examples, please refer to [link to API documentation file or external documentation].

## Security Considerations

The application incorporates security best practices, including:

* Input validation to prevent common security vulnerabilities.
* Token-based authentication for API endpoints.
* Password hashing to protect user credentials.

## Future Improvements

While the current implementation meets the technical assessment requirements, several enhancements could be considered for future iterations:

1. Implementing pagination for API responses to handle large datasets efficiently.
2. Adding support for additional authentication methods (e.g., OAuth2, JWT).
3. Introducing rate-limiting and throttling to protect against abuse.
4. Containerizing the application using Docker for easier deployment and scalability.

## Conclusion

Completing this technical assessment was a valuable experience that allowed me to showcase my backend development skills and knowledge. I am excited about the possibility of joining the Addison Global team and contributing to innovative projects.

If you have any questions or need further information, please feel free to contact me at anderson.dsmartins@outlook.com.

Thank you for considering my submission!