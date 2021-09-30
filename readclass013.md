# Status Codes Based On REST Methods

# In your own words, describe what each group of status code represents:
100’s = These are the informational status codes; They usually tell the client that the main part of the request has been received and the server will attempt to comply with the client’s send request. Like using a different protocol or telling the client that their request will fail before they start sending the text.

- 200’s = These are the symbols of success. They tell the customer that their order has been accepted. In the case of asynchronous processing of a request (202), this does not mean that the request was successfully processed only because it met all validation requirements at the time of sending.

- 300’s = These are redirect codes. They tell the customer that the resource they are requesting is not available at the expected location anymore. This can have multiple reasons, temporary or permanent, but the customer must issue an order to the new location.

- 400’s = These are client error codes. They are all related to invalid requests sent by the client to the server. There are several reasons for this, timeouts, wrong URI, missing authentication, etc. The client sends an invalid input and must confirm that the input parameters are correct before retrying the request.

- 500’s = These are server error codes. It often indicates problems with overburdened servers or unreachable servers behind proxy servers, but sometimes it can be directly related to client requests that lead to error exceptions on the server. These errors can be temporary or permanent. Usually, it is better for the customer to retry the same request.

### What is a status code 202?
Accepted: Often used for asynchronous processing. This code tells the client that the request was valid, but that its processing will finish sometime in the future. The response body should include the URL of the end resource with some information about when it is available, or the URL of some monitoring endpoint that tells the client when the resource is available.

### What is a status code 308?
Permanent Redirect: This tells the client to use another URL to access the resource and not to use the current URL anymore. It’s useful when we have multiple endpoints for a single resource, but we don’t want to read from all of them.

### What code would you use if an update didn’t return data to a client?
204 No Content

### What code would you use if a resource used to exist but no longer does?
414 Request-URI Too Long

### What is the ‘Forbidden’ status code?
403 Forbidden: The client has authorized or does not need to authorize itself, but still does not have permission to access the resource.