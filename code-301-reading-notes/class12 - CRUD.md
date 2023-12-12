# Class 12 - CRUD

## [Status Codes Based on REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
-Some APIs will use just the basic status codes and some APIs will use the entire list of status codes.
- A status code is a number higher than 100 and less than 600.
- The first digit in the status code defines it's class of status
- Understanding the reason for a status code will help troubleshooting efforts

### Questions

1. In your own words, describe what each group of status code represents:
100’s = Informational status code indicating the client send the request and the server will try to comply with request
200’s = Success code indiciating the request was accepted and met all validation requirements
300’s = Redirection code informing the client the resource isn't available at the expected location and requires further action
400’s = Client error codes indiciating an invalid request from the client to sever
500’s = Server error codes indiciating the server has encountered an error or is unable to process the request
2. What is a status code 202?
- Often used for async processing - indiciates the request was valid and wil finish processing in the future
3. What is a status code 308?
- Premanent redirect indicating the rouce is available at a new URL and the client should use the new URL to request the resource
4. What code would you use if an update didn’t return data to a client?
- Code 204 No Content - indiciating the server processed the request but there is no content to return
5. What code would you use if a resource used to exist but no longer does?
- Code 410 Gone - indicating the resource previously exisited, but somehow deleted or removed and unaware of how to access
6. What is the ‘Forbidden’ status code?
- Code 403 indiciating the client does not have permissions to access the resource (inadequate authentication)

## [Build a REST API with Node.js, Express & MongoDB](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
Step-by-step video on how to build a REST API and also explains the why behind each line of code used in the server-API setup

### Questions

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
- It's part of the process to connect the actual MongoDB database to the server
2. What is middleware?
- Code that runs when the sever gets a requests and before it's passed to the server routes
3. What does app.use(express.json()) do?
- Lets server accept JSON as a body instead of a post element or get element
4. What does the /:id mean in a route?
- It's a parameter that we can access to whatever is typed in after the first slash (accessed by req.params.id)
5. What is the difference between PUT and PATCH?
- PATCH creates updates based on the specific user input data and will not update the unspecificed input data
(in other words, if a user only updates their name, then the rest of the information will stay the same and only name will update)
- PUT will update all the information instead of the specified input data
6. How do you make a default value in a schema?
- Use .now method
7. What does a 500 error status code mean?
- Error on the server instead of the user or client side
8. What is the difference between a status 200 and a status 201?
- 201 means sucessfully created whereas 200 means the response was sucessful but nothing was created

## Things I want to know more about
- What's the difference between the startup code npm install express dotenv nodemon and npm install --save-dev express dotenv nodemon? 
- I looked it up in ChatGPT and it says the first is for prod and the second is for test environment. For our class, which one should we use? (My guess is the npm install express dotenv nodemon for prod environments)
- Changing the "devStart" scripts in package.json to nodemon server.js (in our lab it's index.js) at 1:22 (personal reference for server startup with nodemon)
- Why do we put a .env file in the server instead of a .env.local file?