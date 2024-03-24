# API-Testing-Project-Booking-ID
This repository showcases API testing for booking functionalities using Postman and Newman. The focus is on creating, retrieving, updating, and deleting bookings through specific API endpoints.

**Testing Tools:**
Postman: Used for sending API requests, managing test collections, and inspecting responses.
Newman: Utilized for running tests from the command line and generating reports in different formats (e.g., HTML, JSON).

**Testing Coverage:**
CRUD Operations: The project encompasses tests for the following functionalities-
Createbookings (POST)
Getbookings (GET)
Authbooking(POST)
Updatebooking (PUT)
Verifyupdatebooking(PUT)
Deletebooking(DELETE)
Verifydeletebooking(DELETE)

**Booking_Id_api_tests:** This file describes the API testing project.
**Postman_Collections:** This folder holds Postman collections for different testing scenarios.
**Newman_Report:** This folder contains Newman-generated test reports.

**Createbooking:**
Create Booking is typically used to send a POST request to a server to create a new booking or reservation. This POST request includes the necessary data (such as guest details, room type, dates, etc.) in the request body, allowing the server to process and create a new booking entry in its database.
![1](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/502a2841-5e96-4269-a81a-0c46a39ec82e)
![2](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/99acec72-a449-4a4f-9aca-6a800a725e1c)
![3](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/6487153a-cdd6-4143-9674-7c9d7aa6f6e4)

**Getbooking:**
In Postman, a GET method is used to retrieve data from a server or API endpoint. It fetches information from the server without modifying anything, allowing users to view or read data such as user profiles, product listings, or any other resource available on the server.
![4](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/07c4ef72-b039-43f4-b041-040b7e1093cf)

**Authbooking:**
In Postman, an Auth method is used to authenticate and authorize access to protected resources on a server or API endpoint. It allows users to include authentication tokens, API keys, or credentials in the request headers to verify their identity and gain access to restricted data or operations.
![5](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/164123aa-46a0-4973-b5b7-58f494da23e5)

**Updatebooking:**
Update method is used to send a PUT or PATCH request to a server to modify existing data or resources. It allows users to update specific fields or properties of a resource without replacing the entire resource, ensuring efficient and targeted updates to the server's data.
![6](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/efcb7cbb-7189-4269-9ff0-32a2abce47ab)

**VerifyUpdatebooking:**
verify update request API" is used to confirm the successful update of a resource. It involves sending a PUT or PATCH request to modify the resource and then sending a subsequent GET request to ensure that the changes have been applied correctly on the server. This verification step helps ensure the accuracy and completion of the update process.
![7](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/cd554b43-22dd-472a-91fe-ef39c38df1aa)

**Deletebooking:**
Delete method is used to send a request to a server or API endpoint to remove a specific resource. It allows users to delete data entries, records, or other resources from the server's database or storage, effectively removing them from the system.
![810](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/d7a4db50-90fe-4f0e-bc53-8d8cf093c9ad)

**VerifyDeletebooking:**
Verify delete method" is typically used to confirm the successful deletion of a resource. It involves sending a DELETE request to remove the resource and then sending a subsequent GET request to ensure that the resource has been properly deleted from the server. This verification step helps ensure the accuracy and completion of the deletion process.
![9](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/b7c7e860-5458-4466-8036-e3225321f9aa)

**Postman_Environment:**
Environment is used to store and manage variables that can be used across requests in a collection. It allows users to define values such as URLs, API keys, and authentication tokens once and use them dynamically in multiple requests, making it easier to manage and maintain API tests and configurations.
![en](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/128774ba-8333-44d3-aa10-8ee4459d6043)

**Newman_Report:**
Newman report" feature is used to generate detailed test reports for API collections run using the Newman command-line tool. It provides a summary of test results, including pass/fail statuses, response times, and error details, allowing users to analyze and share test results with team members or stakeholders.
![nr](https://github.com/FalguniMalakar/API-Testing-Project-Booking-ID/assets/153453822/e6d12988-ba21-4d60-99af-e7423bbe0bec)

**Newman_RunCommand:**
Newman Run Command is used to execute API collections from the command line using the Newman tool. It allows users to automate the execution of tests, run them in CMD pipelines, and generate detailed reports, enhancing the efficiency and scalability of API testing processes.

**Data.csv:**
Data.csv File is used to demonstrate and test API requests and responses involving CSV (Comma-Separated Values) data format. It allows users to import CSV files, use the data in requests, and test how the API handles CSV data, providing a practical example for working with CSV-based APIs.This file (if applicable) contains sample data used during testing, connected to the environment using variables.
