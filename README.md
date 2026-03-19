# Rise-Internship-Project-3

# AWS Serverless Contact Form Application

## Project Overview

This project demonstrates the development of a **serverless contact form application** using AWS cloud services. The application enables users to submit their details such as name, email, and message through a web interface, and the data is securely stored in a cloud database.

The frontend is built using **HTML and JavaScript**, while the backend leverages AWS serverless technologies to process and store the submitted data without managing any servers.

---

## Technologies Used

- **AWS Lambda** – Serverless compute service  
- **Amazon API Gateway** – API management and request handling  
- **Amazon DynamoDB** – NoSQL database for storing form data  
- **HTML** – Structure of the web form  
- **JavaScript** – Client-side logic and API integration  

---

## Architecture

User → Web Form → API Gateway → AWS Lambda → DynamoDB

- The user submits the form through the browser  
- The request is sent to **API Gateway**  
- API Gateway triggers the **Lambda function**  
- Lambda processes the data and stores it in **DynamoDB**

---

## Features

- Fully **serverless backend architecture**
- Secure storage of user input in cloud database
- REST API integration using API Gateway
- Lightweight and responsive frontend form
- Scalable and cost-efficient infrastructure

---

## Implementation Steps

### 1. Create DynamoDB Table

- Created a table to store contact form data  
- Defined primary key (e.g., `id`)  
- Configured required attributes (name, email, message)

---

### 2. Create Lambda Function

- Developed a Lambda function using supported runtime (e.g., Python/Node.js)  
- Wrote logic to:
  - Receive data from API Gateway  
  - Process and validate input  
  - Store data into DynamoDB  

---

### 3. Configure API Gateway

- Created a REST API  
- Defined a POST method for form submission  
- Integrated API with Lambda function  
- Deployed the API to generate an endpoint URL  

---

### 4. Build Frontend Form

- Created a simple HTML form  
- Used JavaScript to:
  - Capture user input  
  - Send POST request to API endpoint  

---

### 5. Test the Application

- Submitted sample form data  
- Verified successful data storage in DynamoDB  
- Checked API responses and Lambda execution logs  

---

## Project Outcome

- Successfully built a **serverless web application**
- Form data is processed and stored without managing servers
- Backend is scalable and cost-efficient
- Seamless integration between AWS services

---

## Key Learnings

This project helped in understanding:

- Serverless architecture using AWS
- How API Gateway interacts with Lambda
- Data storage using DynamoDB
- Building and integrating REST APIs
- Handling client-server communication in web apps

---

## Screenshots

(Add your project screenshots here)

---

## Future Enhancements

Possible improvements include:

- Adding **input validation and error handling**
- Implementing **email notifications (SNS/SES)**
- Adding **authentication using AWS Cognito**
- Creating a dashboard to view submitted data
- Improving UI/UX of the contact form

---

## Repository Purpose

This repository showcases my hands-on experience in building a **serverless application using AWS services**. It highlights the integration of Lambda, API Gateway, and DynamoDB to create a scalable and efficient backend system as part of my cloud and DevOps learning journey.
