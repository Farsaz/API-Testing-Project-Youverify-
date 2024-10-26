# API Testing and E-Commerce Automation

## Overview
This repository contains a collection of API tests performed using Postman, focusing on the My IP API, as well as test automation scripts for an e-commerce (Jumia) platform. The purpose of this repository is to validate the functionality of the API and ensure that the automated tests cover various functionalities for proper operation and cross-browser compatibility.

## API Testing Project

### API Overview
- **API**: My IP API
- **Endpoint**: [https://api.myip.com](https://api.myip.com)

### Test Cases
The following test cases were executed:

1. **GET Request** to retrieve IP information.
   - **Expected Status Code**: 200
   - **Response Fields**: 
     - `ip`: IP address
     - `country`: Country location in English
     - `cc`: Two-letter country code (ISO 3166-1 alpha-2)

### Results
- **Test Outcome**: PASS
- **Status Code**: 200
- **Response Validation**:
  - IP field is present: PASS
  - Country field is present: PASS
  - CC field is present: PASS

### Postman Collection
You can find the Postman collection (https://api.postman.com/collections/36899778-7d04dfa9-3f7c-4d74-ad7b-4984b2ffd12e?access_key=PMAT-01JB4BX49Z60MJ48JHMNFSB604).

### Performance Test Report
The performance test report is included in the PDF document attached.

## Test Automation Project

### Overview
The test automation project aims to verify the functionality of an e-commerce platform using Cypress. The tests cover various functionalities to ensure proper operation and cross-browser compatibility, ensuring a reliable user experience.

### Environment
- **Browsers**: Tested on Chrome (Version 130.0.6723.59) and Firefox (Version 131.0.3).
- **Cypress Version**: ^13.14.2
- **Operating System**: macOS
- **Programming Language**: JavaScript

### Getting Started

#### Prerequisites
1. **Node.js**: Ensure Node.js is installed on your machine.
2. **Cypress**: Make sure Cypress is installed in your project.

### Test Cases
The test automation covers functionalities including but not limited to:
- Product search.
- Shopping cart operations (add, update, remove items).
- Checkout process validation.
- Test rerun mechanism
- Cross-browser functionality to ensure a consistent user experience.

