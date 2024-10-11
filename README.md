API Automation with Postman - CRISP
Overview
This project contains a Postman collection for automating API testing of the CRISP GET API. The collection includes various requests to check response status, and response time.

Prerequisites
Postman: Ensure you have Postman installed. You can download it.
Node.js: Required for running any additional scripts.

Getting Started
1. Clone or Download the Repository
Clone the repository to your local machine using Git or download it as a ZIP file.

https://github.com/ranjitakulkarni/Postman-Collection-CRISP

Copy code
git clone https://github.com/ranjitakulkarni/Postman-Collection-CRISP.git

2. Open Postman
Launch Postman on your computer.

3. Import the Collection
Click the "Import" button in the top left corner.
Choose the "Link" tab.
Paste the URL to the Postman collection:

Copy code
https://raw.githubusercontent.com/ranjitakulkarni/Postman-Collection-CRISP/refs/heads/main/Assignment.postman_collection.json
Click "Continue" and then "Import".

4. Set Up Environment Variables
If your requests rely on specific environment variables, set them up as follows:

Click on the gear icon in the top right corner and select "Manage Environments".
Create a new environment [QA] and define variables such as: 
baseUrl: https://apimgmt-dev-crisp.azure-api.net

5. Execute Tests
Select the imported collection from the left sidebar.
Choose a request to execute.
Click the "Send" button to see the response.

7. Run Collection Runner (Optional)
To run all requests in the collection:
Click on the collection name and select "Run".Configure any options (like delay, iteration count) and click "Run".

List of Test cases for Crisp 


