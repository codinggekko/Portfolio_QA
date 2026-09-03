TC-02 — Latitude upper boundary

Test Case: Verify that the API accepts the maximum valid latitude.

Method: GET

Endpoint:
https://api.open-meteo.com/v1/forecast

Test data:

Latitude: 90.00
Longitude: 17.10

Steps:

Send a GET request with the specified latitude and longitude.
Check the HTTP response status.
Check the response body.

Expected result:

Response status is 200 OK.
Response body is returned in JSON format.
Weather data is provided for the requested coordinates.
