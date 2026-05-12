# API Test Cases

## TC-API-01 – Successful Login
Request: POST /login  
Expected status: 200 OK  
Expected response: Auth token returned.

## TC-API-02 – Invalid Login
Request: POST /login  
Expected status: 401 Unauthorized  
Expected response: Error message.
