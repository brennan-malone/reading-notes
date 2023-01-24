# CRUD

## Status codes based on REST methods

In your own words, describe what each group of status code represents:

100’s = Informational.
200’s = Sucess codes.
300’s = Redirection codes.
400’s = client error codes.
500’s = Server error codes.
What is a status code 202? Accepted, process was valid, but will finish processing sometime in the future.
What is a status code 308? Permanent Redirect, tells the client to use another URL to access the resource.
What code would you use if an update didn’t return data to a client? 204 no content.
What code would you use if a resource used to exist but no longer does? 410 Gone.
What is the ‘Forbidden’ status code? 403 forbidden.

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

Why do we need to pull our MongoDB database string out of our server and put it into our .env? 
because it has sensitive information and we don't want to upload the username and password up to github.
What is middleware?
gives us functionality that such as routes within express.
What does app.use(express.json()) do?
lets our server accept JSON in the body.
What does the /:id mean in a route?
that is a route parameter that captures the values specified at their position and populated in the req.params object.
What is the difference between PUT and PATCH?
PUT is a technique of altering resources when the client transmits data that revamps the whole resource.
PATCH is a technique for transforming the resources when the client transmits partial data.
How do you make a default value in a schema?
default: something within the options object.
What does a 500 error status code mean?
it is a generic error response. It means that the server encountered an unexpected condition that prevented it from fufilling the request.
What is the difference between a status 200 and a status 201?
200 is a everything is okay
201 means that a new resource has been created when that request was filled.
