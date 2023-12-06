# Class 08 - APIs

## [APIs](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
Design APIs around good resource practices, adhere to RESTful principles, and ensure consistency and simplicity in URI structures.

![API Operations - HTTP Methods Table](./assets/API%20Operations%20-%20HTTP%20Methods%20table.png) - from article
### Questions

1. What does REST stand for?
Representational State Transfer
2. REST APIs are designed around a ____.
Resource - any time of object, service or data that can be accessed by the client
3. What is an identifier of a resource? Give an example.
A uniform resource identifier (URI) that uniquely identifies a resource
4. What are the most common HTTP verbs?
GET, POST, PUT, PATCH, and DELETE
5. What should the URIs be based on?
Based on nouns, not verbs
6. Give an example of a good URI.
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid

- examples from article
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
It's a bad thing because it requires a lot of web page computing power. 'Chatty' web API means an application sends multiple requests to retrieve the requested data
8. What status code does a successful GET request return?
Returns HTTP status code 200 (OK)
9. What status code does an unsuccessful GET request return?
Return 404 (Not Found)
10. What status code does a successful POST request return?
Returns HTTP status code 201 (Created)
11. What status code does a successful DELETE request return?
Respond with HTTP status code 204 (No Content)

## Additional Resources

## [RegExr](https://canvas.instructure.com/courses/8071579/discussion_topics/20115110)

## [Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

## [Regex 101](https://regex101.com/)

## Things I want to know more about
- I think it's pretty cool to understand the background behind the words used for a URL and how it navigates to the correct resource
- The reading says get, post, put, patch and delete are the most common RESTful web APIs, but what are the uncommon ones?
- Future features for city-explorer will incorporate more APIs. I'm assuming we'll have to figure out a way to use asynchronous operations to ensure all the data renders at the same time to optimize the user experience.
- What are best practices to ensure our web APIs are not "chatty"?
