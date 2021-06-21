# CRUD

## Status Codes Based On REST Methods

In your own words, describe what each group of status code represents:
**100’s** =  informational status codes; request will fail before they start sending the body.

**200’s** = success codes; request accepted.

**300’s** = redirection codes; not available.

**400’s** = error codes; invalid requests .

**500’s** = server error codes; overwhelmed servers or unreachable servers.

**202** = asynchronous processing.

**308** =  Permanent Redirect; indicates that other url should be used.

**204 No Content** no returned data to the client.

**410 Gone** = resource used to exist but no longer does.

**403 Forbidden** = no permissions to access the resource.

## Build A REST API With Node.js, Express, & MongoDB - Quick

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

 for storing sensitive data (not to be pushed)

2. What is middleware?

system with functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.

3. What does app.use(express.json()) do? 

allow us to use express methods.

4. What does the /:id mean in a route?

id is the unique instance field (_id) that is given to each Mongoose model instance by default.

5. What is the difference between PUT and PATCH?

PUT = create , PATCH = update

6. How do you make a default value in a schema? 

by creating a new document without that path set, the default will kick in.

7. What does a 500 error status code mean? 

500 Internal Server Error

8. What is the difference between a status 200 and a status 201?

200 =  accessible  resource, 201 = create operations


References:

* [status codes](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

* [Video](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)