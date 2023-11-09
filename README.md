# London Cafe API

This API provides a list of all cafes in the area of London. It is a RESTful API that allows users to retrieve information about cafes, including their names, coffe-price, information like is cafe have wifi,have toilet and contact information.

## Endpoints

### GET /cafes
- Returns a list of all cafes in the area of London.

### GET /cafes/{id}
- Returns the details of a specific cafe, identified by its unique ID.

### POST /cafes
- Adds a new cafe to the list.

### PUT /cafes/{id}
- Updates the details of a specific cafe.

### DELETE /cafes/{id}
- Deletes a specific cafe from the list.

## Request Parameters

- `id` (int) - The unique identifier of a cafe.

## Response Format

The API returns data in JSON format, with the following fields for each cafe:

- `id` (int) - The unique identifier of the cafe.
- `name` (string) - The name of the cafe.
- `address` (string) - The address of the cafe.
- `contact` (string) - The contact details of the cafe.

## Usage

To use the API, send HTTP requests to the specified endpoints with the appropriate request parameters. The API will respond with the requested data in JSON format.

## Authentication

The API does not require authentication to access the data. However, for adding or updating cafes, authentication may be required.

## Rate Limiting

There is no rate limiting on the API requests, but excessive usage may result in temporary restrictions.

## Errors

If an error occurs, the API will respond with an appropriate HTTP status code and an error message in the response body.

## Contact

For any questions or support, please contact us at [contact@example.com](panwarakhil033@gmail.com).
