# What does REST stand for?

Is an architectural style that allows computers to interact with one other to facilitate standards amongst computer systems on the web.

REST APIs are designed around a \_\_.
Resources

## What is an identifer of a resource? Give an example?

- GET
- POST
- PUT
- PATCH
- DELETE

## What should the URIs be based on?

Resource URIs are based on nouns and not verbs (the resource) (the operations on the resource).

## Give an example of a good URI?

example.com/good-uri-design

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

This is because it requires many network calls to delay a program, hence chatted APIs are seen to be poor quality. Every call carries an overhead data (i.e. sender information, headers, authentication) that slows down the program and network delay each request.

## What status code does a successful GET request return?

It returns an HTTP status code 200 (OK).

## What status code does an unsuccessful GET request return?

It returns a 404 (Not Found).

## What status code does a successful POST request return?

Returns HTTP status code 201 (Created).

## What status code does a successful DELETE request return?

Respond with HTTP status code 204 (No Content).
