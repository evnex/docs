# Errors

<aside class="notice">The Particle API uses the following error codes:</aside>

Error Code | Meaning
---------- | -------
<<<<<<< HEAD
200 | API call successfully delivered to the device and executed.
400 | Your request is not understood by the device, or the requested subresource (variable/function) has not been exposed.
401 | Unauthorized - Your access token is not valid.
403 | Forbidden - Your access token is not authorized to interface with this device.
404 | Not Found - The device you requested is not currently connected to the cloud.
408 | Timed Out - The cloud experienced a significant delay when trying to reach the device.
500 | Server errors - Fail whale. Something's wrong on our end.

=======
400 | Bad Request -- Your request sucks
401 | Unauthorized -- Your API key is wrong
403 | Forbidden -- The kitten requested is hidden for administrators only
404 | Not Found -- The specified kitten could not be found
405 | Method Not Allowed -- You tried to access a kitten with an invalid method
406 | Not Acceptable -- You requested a format that isn't json
410 | Gone -- The kitten requested has been removed from our servers
418 | I'm a teapot
429 | Too Many Requests -- You're requesting too many kittens! Slow down!
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
>>>>>>> d3f7825977550225fd8fab05e727ea46864fb05a
