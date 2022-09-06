
# CRUD

## In your own words, describe what each group of status code represents:

- ### 100's =they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. 

- ### 200's= they tell the client that its request was accepted

- ### 300's=They tell the client that the resource they are requesting isn’t available at the expected location anymore

- ### 400's= They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc

- ### 500's= Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server


## What is a status code 202? 
### met all validation requirements at the time of sending.

## What is a status code 308?
### tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

## What code would you use if an update didn't return data to a client?
### 204 No Content

## What code would you use if a resource used to exist but no longer does?
### create asynchronous processing

## What is the 'Forbidden' status code?
### 403

# Why do we need to pull our MongoDB database string out of our server and put it into our .env?
### to protect our data

# What is middleware?
## oftware that provides common services and capabilities to applications outside of what's offered by the operating system

# What does app.use(express.json()) do?
## it parses incoming JSON requests and puts the parsed data in req.

# What does the /:id mean in a route?
## parameter

# What is the difference between PUT and PATCH?
## PUT is a method of modifying resource where the client sends data that updates the entire resource 
## PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data

# How do you make a default value in a schema?
##  create a new document without that path set

# What does a 500 error status code mean?
## the server encountered an unexpected condition that prevented it from fulfilling the request

# What is the difference between a status 200 and a status 201?



## The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed

## A 201 status code indicates that a request was successful and as a result, a resource has been created