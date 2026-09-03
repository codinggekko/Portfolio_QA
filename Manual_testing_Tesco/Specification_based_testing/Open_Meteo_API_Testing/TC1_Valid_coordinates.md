
TC-01 — Valid coordinates

Test Case: Verify that the API returns weather data for valid latitude and longitude.

Method: GET

Endpoint:
https://api.open-meteo.com/v1/forecast

Test data:

Latitude: 48.1486
Longitude: 17.1077

Steps:

Send a GET request with the specified latitude and longitude.
Check the HTTP response status.
Check the response body.

Expected result:

Response status is 200 OK.
Response body is returned in JSON format.
Weather data is provided for the requested coordinates.
