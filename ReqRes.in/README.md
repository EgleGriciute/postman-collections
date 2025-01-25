# ReqRes API Postman Collection

This repository contains the Postman collection for the **ReqRes API**, an API for testing and demonstrating RESTful APIs.

## Collection Details

- **Collection Name:** ReqRes.in
- **Postman Collection Link:** [ReqRes Collection](https://eglegriciute.postman.co/workspace/New-Team-Workspace~32741dd8-a336-42e7-ba32-8dfd7a50a528/collection/18306743-dfa6c315-0552-46c1-b038-cf950448bd01?action=share&source=collection_link&creator=18306743)
- **Schema:** [Postman Collection Schema](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Available API Endpoints

1. **List Users** (`GET /api/users?page=2`)  
   Returns a paginated list of users.

2. **List a Single User** (`GET /api/users/{id}`)  
   Fetches a single user by ID.

3. **Create a User** (`POST /api/users`)  
   Creates a new user by providing `name` and `job`.

4. **Update User** (`PUT /api/users/{id}`)  
   Updates a user's details.

5. **Delete User** (`DELETE /api/users/{id}`)  
   Deletes a user by ID.

6. **Register and Login**

   - `POST /api/register`: Successful and unsuccessful user registration.
   - `POST /api/login`: Successful and unsuccessful login.

7. **List Resources** (`GET /api/unknown`)  
   Returns a list of resources.

8. **Single Resource** (`GET /api/unknown/{id}`)  
   Fetches a specific resource.

## Running the Collection

To use the collection:

1. Import the Postman collection into Postman.
2. Set up environment variables (e.g., `base_url`).
3. Run the desired request and check tests.

## Tests

Each request contains test scripts that validate the response, including:

- Status code checks (e.g., `200 OK`, `404 Not Found`).
- Data validation (e.g., user existence, matching values).
