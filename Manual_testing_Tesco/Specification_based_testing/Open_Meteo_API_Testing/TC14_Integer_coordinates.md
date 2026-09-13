TC-14 — Integer coordinates

Test Case: Verify that the API accepts integer coordinates and returns weather data.

Method: GET

Endpoint:
https://api.open-meteo.com/v1/forecast

Test data:

Latitude: 48
Longitude: 17

Steps:

Send a GET request with the specified latitude and longitude.
Check the HTTP response status.
Check the response body.

Expected result:

API accepts the request successfully.
API returns HTTP 200 OK.
Response body is returned in JSON format.
