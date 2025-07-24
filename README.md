📘 Postman API Testing Project – Simple Book API

This repository contains a Postman + Newman API testing project for the Simple Book API. It demonstrates API test automation, scripting, and reporting for various endpoints like books and orders.

✅ Tools Used

Postman – for API test creation and management

Newman – for running collections via CLI

HTML Reporter – for clean visual test reports

JavaScript – for test scripts inside Postman

📂 Folder Structure

postman-api-testing-project/

├── collections/

   └── simple-book-api.postman_collection.json

├── environment/

   └── simple-book-api-env.postman_environment.json

├── data/

   └── testdata.csv        

├── reports/

   └── newman-report.html

├── README.md

🔧 How to Run the Tests

(Inside the folder run)

npm install -g newman 
npm install -g newman-reporter-htmlextra
newman run collections/simple-book-api.postman_collection.json -e environment/simple-book-api-env.postman_environment.json -r htmlextra

Features Covered

✅ Status code validation

✅ Response structure and data checks

✅ Scripting using pm.test() and pm.response

✅ Filtering JSON data

✅ Use of environment variables ({{baseURL}}, etc.)

✅ Dynamic chaining and data sharing across requests

✅ Collection runner (via Newman)

✅ HTML test reporting


