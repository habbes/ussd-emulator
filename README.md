# ussd-emulator
Basic AJAX-Based USSD Emulator

This Emulator allows you to test your USSD endpoints and is compatible with request parameters sent by [Africastaling's API](http://africastalking.com).

## Limitations
At the moment it only send `GET` requests.
Since it's based on AJAX, the requests might fail due to **CORS** related errors if it's not served from the same server handling the requests.
