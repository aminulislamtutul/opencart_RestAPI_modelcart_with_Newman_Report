### **opencart RestAPI modelcart**
OpenCart is a free open-source e-commerce platform for online merchants. OpenCart offers a professional and reliable foundation for building a successful online store.
### **Feature**
- Tests for GET, PUT requests
- Collection of tests covering different API endpoints
- Environment setup for easy switching between environments
- Pre-request scripts for data setup
- Test scripts for validations
## API Documentation
- https://documenter.getpostman.com/view/46763324/2sB3BHjTYt
### **Technoloy Used**
- Postman
- Newman
### **Prerequisite**
- Node.js
- Newman
- Newman html Report Library
### **Installation**
1. Postman: If you haven't already, [download and install Postman.](https://www.postman.com/downloads/)
2. Clone the repository:
 ```console 
  git clone https://github.com/aminulislamtutul/opencart_RestAPI_modelcart_with_Newman_Report.git
```
3. Import the Postman collection:
    - Open Postman.
    - Click on the Import button.
    - Select the file from the repository.
4. Import the Postman environment:
    - In Postman, click on the gear icon in the top right corner.
    - Select **Import** and choose the file.
5. Newman and Report Installation Process:
    - Newman Install Command:
     ```console 
      npm install -g newman
    ```
    - Newman html Report Install Command:
     ```console 
      npm install -g newman-reporter-htmlextra
    ```
### **Usage**
1. Select Environment:
    -   In Postman, select the appropriate environment (e.g., Development, Production) from the top-right dropdown.
2. Run Collection:
    -   Select the imported collection from the Collections sidebar.
    -   Click on the Runner button to open the collection runner.
    -   Select the desired environment.
    -   Click Start Test to run the collection.
3. View Results:
    -   Once the tests are complete, view the results in the Runner tab.
    -   Detailed test results can be viewed for each request.
## **Testing**

## Test Case Scenarios:
## _**1. Create session/Token**_
### Request URL: http://192.168.0.106/opencart/upload/index.php?route=/api/login
### Request Method: POST
 **Response Body:**
```console
{
    "success": "Success: API session successfully started!",
    "api_token": "a075009d265d79b8773e9655bc"
}
```
## _**2. Add product to the cart**_
