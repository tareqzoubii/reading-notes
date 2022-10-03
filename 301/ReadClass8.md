**_What does REST stand for?_**
>REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP.
**_REST APIs are designed around a ____._**
>RESOURCE
**_What is an identifier of a resource? Give an example._**
>A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be https://adventure-works.com/orders/1
**_What are the most common HTTP verbs?_**
>The most common operations are GET, POST, PUT, PATCH, and DELETE.
**_What should the URIs be based on?_**
>URIs should be based on nouns (the resource) and not verbs (the operations on the resource).
**_Give an example of a good URI._**
>/customers/5/orders
**_What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?_**
>web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request.
**_What status code does a successful GET request return?_**
>200
**_What status code does an unsuccessful GET request return?_**
>404!
**_What status code does a successful POST request return?_**
>201
**_What status code does a successful DELETE request return_**
>204
[RESOURCE](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## Things I want to know more about
>i want to know more about API and how to create alot of methods on it 