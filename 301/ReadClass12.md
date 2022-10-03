**_In your own words, describe what each group of status code represents:_**

_100's = that the header part of the request has been received and the server will try to comply with a transmission demand_

_200's = request is accepted_
_300's = the resource they are requesting isn’t available_
_400's = A client is sending incorrect input there is something wrong_
_500's = retry the request_

**_What is a status code 202?_**
>his code tells the client that the request was valid, but its processing will finish sometime in the future

**_What is a status code 308?_**
>This tells the client to use another URL to access the resource and not use the current URL anymore. 
**_What code would you use if an update didn't return data to a client?_**
>204 No Content!

**_What code would you use if a resource used to exist but no longer does?_**
>401 Gone!
**_What is the 'Forbidden' status code?_**
>403

**_Why do we need to pull our MongoDB database string out of our server and put it into our .env?_**
>because we dont want any one to see it 
**_What is middleware?_**
>What is middleware with example?
Middleware is software which lies between an operating system and the applications running on it.
**_What does app.use(express.json()) do?_**
>it send the data in a json file way (OBJECT) 
**_What does the /:id mean in a route?_**
>selected a specific id we wan't if we need to delete something
**_What is the difference between PUT and PATCH?_**
>put it use to read
**_How do you make a default value in a schema?_**
>mongoose only sets defaults on insert.
**_What does a 500 error status code mean?_**
>t means that the server encountered an unexpected condition that prevented it from fulfilling the request.
**_What is the difference between a status 200 and a status 201?_**
>200 OK - Some people think a delete function of any kind should return the deleted element, so a representation of the deleted element can be included in the response body.
>201 Created - The most fitting for Create operations. This code should signal backend-side resource creation and come along with a Location header that defines the most specific URL for that newly created resource. It’s also a good idea to include appropriate representation of the resource or at least one or more URLs to that resource in the response body.