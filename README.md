# API Testing Project

## Overview
This project contains a collection of API tests performed using Postman, focusing on the My IP API. The purpose of this testing is to validate the API's functionality and ensure it returns the expected data structure.

## API Tested
- **API**: My IP API
- **Endpoint**: [https://api.myip.com](https://api.myip.com)

## Test Cases
The following test cases were executed:
1. **GET Request** to retrieve IP information.
   - **Expected Status Code**: 200
   - **Response Fields**: 
     - `ip`: IP address
     - `country`: Country location in English
     - `cc`: Two-letter country code (ISO 3166-1 alpha-2)

## Results
- **Test Outcome**: PASS
- **Status Code**: 200
- **Response**:
  - IP field is present: PASS
  - Country field is present: PASS
  - CC field is present: PASS

## Postman Collection
You can find the Postman collection (https://api.postman.com/collections/36899778-7d04dfa9-3f7c-4d74-ad7b-4984b2ffd12e?access_key=PMAT-01JB4BX49Z60MJ48JHMNFSB604).

## Performance Test Report
The performance test report is included in the PDF document attached.

## Submission
Please review the provided files for further details and the test results.
