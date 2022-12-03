# Django CRUD and Forms

## HTML form :is a group of one or more fields/widgets on a web page, which can be used to collect information from users for submission to a server

## Forms is a secure way of sharing data with the server, as they allow us to send data in POST requests with cross-site request forgery protection.
- action: The resource/URL where data is to be sent for processing when the form is submitted. If this is not set (or set to an empty string), then the form will be submitted back to the current page URL.
- method: The HTTP method used to send the data: post or get
- 1)The POST method should always be used if the data is going to result in a change to the server's database
- 2)The GET method should only be used for forms that don't change user data (for example, a search form)

## the main things that Django's form handling:
- Display the default form the first time it is requested by the uses
- Receive data from a submit request and bind it to the form.
- Clean and validate the data
- If any data is invalid, re-display the form, this time with any user populated values and error messages for the problem fields
- If all data is valid, perform required actions (such as save the data, send an email, return the result of a search, upload a file, and so on).
- Once all actions are complete, redirect the user to another page
