# Number Classification API

## Overview

This API takes a number as input and returns mathematical properties about it, along with a fun fact.

## Technology Stack

- **Backend:** AWS Lambda (Python)
- **API Gateway:** HTTP API
- **Version Control:** GitHub
- **Hosting:** Publicly accessible endpoint

## Features

- Checks if a number is prime or perfect.
- Computes the sum of its digits.
- Identifies special properties (e.g., Armstrong number, even/odd).
- Returns a fun fact about the number.
- Handles CORS and returns JSON responses.

## API Endpoint

**GET** (https://taeiej1dj0.execute-api.us-east-1.amazonaws.com/prod/api/classify-number?number=371)

### Example Response (200 OK)

![Screenshot (53)](https://github.com/user-attachments/assets/0e6e4845-fff3-49f6-ac77-5577e77f6b9c)


### Error Response (400 Bad Request)

![Screenshot (54)](https://github.com/user-attachments/assets/c650b1a4-2c76-48e5-a720-cc3bfb94fe99)


## How to Use
[Read Here](https://dev.to/tony_uketui_6cca68c7eba02/building-a-number-classification-api-using-aws-lambda-4cf7)

## Deployment

- Hosted on AWS Lambda & API Gateway.
- Fast response time (<500ms).
