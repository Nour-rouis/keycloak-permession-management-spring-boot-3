Keycloak Integration with Spring Boot 3
This project demonstrates how to secure a Spring Boot application using Keycloak, a powerful open-source Identity and Access Management tool.

Features
Single Sign-On (SSO) with OpenID Connect
Role-Based Access Control (RBAC)
Fine-Grained Authorization
Prerequisites
Java 17+
Maven
Keycloak Server 21+
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Installation
Clone the repository:
git clone git@github.com:ali-bouali/keycloak-integration-with-spring-boot-3.git
Navigate into the project directory:
cd your-repository-name
Use Maven to build the project:
mvn clean install
You can then run the Spring Boot application using:
mvn spring-boot:run
Keycloak Setup
Run the docker-compose file:
docker-compose up -d
Navigate to Keycloak Admin UI Console
Create a new Real and name ut Alibou or update the application.yml file and specify your Realm name
Create Roles
Create Users
Assign roles to users
Usage
TBD

Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

License
This project is licensed under the MIT License - see the LICENSE.md file for details
