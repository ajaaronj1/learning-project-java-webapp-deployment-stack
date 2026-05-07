# learning-project-java-webapp-deployment-stack

## Project Overview

This project documents the deployment workflow of a Java web application using:

- Maven
- Apache Tomcat
- NGINX
- AWS EC2

The focus of this project is not application development, but understanding the deployment pipeline, runtime behavior, reverse proxy architecture, troubleshooting process, and interactions between system components.

---

## What This Project Demonstrates

- Maven build and packaging lifecycle
- WAR deployment using Apache Tomcat
- JSP runtime compilation behavior
- Reverse proxy configuration using NGINX
- Linux server administration concepts
- AWS EC2 networking and security group configuration
- End-to-end request flow
- Troubleshooting and debugging methodology

---

## Deployment Stack

Client Browser
↓
NGINX (Port 80)
↓
Apache Tomcat (Port 8080)
↓
Java Web Application (WAR)

---

## Key Concepts Explored

- Compilation vs packaging
- Maven build lifecycle
- WAR file structure
- Tomcat runtime behavior
- ROOT.war deployment mapping
- Reverse proxy architecture
- NGINX configuration hierarchy
- Request-response lifecycle
- Cloud firewall/security group behavior

---

## Source Application Reference

The source application used in this deployment exercise was obtained from:

[java_proj_sample GitHub Repository](https://github.com/AmalkumarG/java_proj_sample?utm_source=chatgpt.com)

This repository was used for learning and deployment purposes.

---

## Full Documentation

The complete deployment report is available here:

- [deployment-report.pdf](report/deployment-report.pdf)

The report includes:
- conceptual explanations
- hierarchical system views
- deployment workflow
- troubleshooting details
- runtime behavior explanations
- architectural flow diagrams

---

## Technologies Used

- Java
- Maven
- Apache Tomcat 9
- NGINX
- Amazon Elastic Compute Cloud (Amazon EC2)
- Amazon Linux

---

## Important Notes

- The application source code was not authored by me.
- The focus of this repository is deployment architecture, runtime behavior, infrastructure concepts, and troubleshooting.
- The project was used as a learning exercise to understand how Java web applications are built, deployed, and exposed through layered system components.

