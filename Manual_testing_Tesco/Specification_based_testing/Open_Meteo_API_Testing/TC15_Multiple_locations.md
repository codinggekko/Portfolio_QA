
TC-15 — Multiple locations

Test Case: Verify that the API returns weather data for two locations with valid coordinates.

Method: GET

Endpoint: https://api.open-meteo.com/v1/forecast

Test data:

Latitude: 48.14, 51.50 Longitude: 17.10, 0.12

Steps:

Send a GET request with the specified latitude and longitude for two different locations. Check the HTTP response status. Check the response body.

Expected result:

API accepts the request successfully. API returns HTTP 200 OK. Response body is returned in JSON as a list of structures. 
