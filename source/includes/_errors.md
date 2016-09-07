# Errors

<aside class="notice">The Particle API uses the following error codes:</aside>

Error Code | Meaning
---------- | -------
200 | API call successfully delivered to the device and executed.
400 | Your request is not understood by the device, or the requested subresource (variable/function) has not been exposed.
401 | Unauthorized - Your access token is not valid.
403 | Forbidden - Your access token is not authorized to interface with this device.
404 | Not Found - The device you requested is not currently connected to the cloud.
408 | Timed Out - The cloud experienced a significant delay when trying to reach the device.
500 | Server errors - Fail whale. Something's wrong on our end.

