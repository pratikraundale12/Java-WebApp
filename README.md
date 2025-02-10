# Simple Java Web Application

This project is a simple Java web application demonstrating a CI/CD pipeline using Jenkins, Maven, and Apache Tomcat.

## Project Structure
src/main
├── java/ # Java source files
├── resources/ # Configuration and resource files
└── webapp/ # Web application files (e.g., JSP, HTML, CSS)
target/ # Compiled and packaged output (e.g., WAR file)
pom.xml # Maven configuration file
README.md # Project documentation

Copy

## Tools Used

- **Jenkins**: For continuous integration and deployment.
- **Maven**: For building and managing the project.
- **Apache Tomcat**: For deploying and running the web application.

## CI/CD Pipeline

The CI/CD pipeline is set up to automate the build, test, and deployment process:
1. **Build**: Maven is used to compile the code and package it into a WAR file.
2. **Deploy**: The WAR file is deployed to Apache Tomcat for testing and production.
3. **Automation**: Jenkins orchestrates the entire pipeline, ensuring seamless integration and deployment.

## Commit History

- **Main Commit**: Updated `index.jsp` and configured the CI/CD pipeline.
- **First Commit**: Initial project setup with `pom.xml` and basic structure.

---

For more details, refer to the project files or contact the maintainer.
