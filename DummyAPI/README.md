# Postman Collection for DummyJSON API

This repository contains a Postman collection for the [DummyJSON API](https://dummyjson.com/) to test and interact with various endpoints.

## Overview

1. Created a Postman collection based on the [DummyJSON API](https://dummyjson.com/).
2. Implemented requests as per the API documentation.
3. Added tests to:
   - Check status codes, request formats, and verify no 'error' elements in the JSON.
   - Test comment count for Post with id=46.

## API Endpoints

- **Products**: `/products`
- **Users**: `/users`
- **Comments**: `/comments`
- **Authentication**: `/auth`

See the full API docs [here](https://dummyjson.com/docs).

## Test Cases

- **Status Code Test**: Verifies expected HTTP status codes.
- **Request Format Test**: Ensures requests are correctly formatted.
- **Error Element Check**: Confirms no 'error' elements in responses.
- **Comment Count Test**: Checks how many comments Post id=46 has.

## Environment Variables

- **base_url**: `https://dummyjson.com/`
- **AccessToken**: Used for authenticated requests.
- **RefreshToken**: Used to refresh the access token.

Set these in your Postman environment.

## How to Use

1. Import the collection into Postman.
2. Set up the environment variables (`base_url`, `AccessToken`, `RefreshToken`).
3. Run the requests and tests.

For more details on using variables, refer to [Postman Variables Docs](https://learning.postman.com/docs/sending-requests/variables/variables/).
