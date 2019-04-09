## Test case for geolocationAPI

This test covers:

 - Foword lookup 
 - Reverse Lookup
 - Viewport Biasing
 - Region Biasing
 - Component Filtering
 - Address Retrieving form a Place ID

The basic fuction of the geolocation API is the conversion of the address into geophraphic coordinates and vice versa, therefore the smoke test represents these two basic fuctions.
In the SoupUI the smoke test is automated.
A test case for all API functions is also made, and the same is automated.
The Google API key must be entered in the test so that it can run.
In the Method called GET under Method Parameters is the parameter named key, simply paste the Google API key into the value field.