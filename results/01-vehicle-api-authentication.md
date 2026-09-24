# Vehicle API Authentication Test

## Endpoint Tested

GET `/identity/api/v2/vehicle/vehicles`

## Test Method

A GET request was sent to the vehicle API endpoint without providing an authentication token.

Command used:

`curl -i http://127.0.0.1:8888/identity/api/v2/vehicle/vehicles`

## Result

The server returned:

`HTTP/1.1 401 Unauthorized`

The response indicated:

`Invalid Token`

## Observation

The vehicle API endpoint requires authentication and did not return vehicle data when a valid authentication token was not provided.

## Conclusion

This test confirms that the tested vehicle endpoint is protected by an authentication mechanism.





