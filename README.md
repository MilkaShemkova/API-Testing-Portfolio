# 🚀 API Testing Portfolio: FoodieApp

This repository showcases practical skills in Web API testing, including request execution, response validation, and using Postman to create structured, runnable test collections.

---

## 📜 1. Description

This project consists of a Postman collection designed to test the core **CRUD** (Create, Read, Update, Delete) and **Auth** (Authentication) operations of the FoodieApp Web API. Key activities include:
* Testing HTTP methods: GET, POST, PUT, and DELETE.
* Validation of Status Codes and Response Data structure.


## 🔗 2. Deployment link

**Tested API:** FoodieApp API (Staging Environment).

* **Note on Execution:** As this is an older test collection, some requests (e.g., PUT/DELETE) may fail due to **expired authentication tokens** or the **deletion of the test data** used previously. To run the full collection successfully, please ensure you **run the authentication request first** to obtain a valid token and re-create any necessary test data.

## 💻 3. Technology Stack

* **Primary Tool:** **Postman** (used for API request creation, execution, and documentation).
* **Methodology:** API Functional Testing.
* **Protocol:** HTTP/HTTPS.
* **Artifact:** **`FoodieApp.postman_collection.json`**

## 📄 4. API Documentation

The complete API documentation, including request structures, validation tests, and the dependency chain between requests, is contained within the JSON collection file.

* **File Access:** The file **`FoodieApp.postman_collection.json`** is available in this repository. Please import it into Postman to review all content.

## 📐 5. Design Diagram

**Note:** For API testing, the "Design Diagram" often represents the Test Flow or Request Chain. Our test flow followed the sequence: **Auth Request → Read/GET Request → Create/POST Request → Delete/DELETE Request.**

## 📸 6. Screenshots

Examples demonstrating successful execution and automated validation of the API tests:

### Successful GET Request
![Screenshot of a successful GET request in Postman](Screenshot 2025-10-23 145650.png)

### Automated Validation Tests
![Screenshot of Postman Tests tab for validation](Screenshot 2025-10-23 151427.png)
