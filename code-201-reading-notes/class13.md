# Class 13 - Local Storage

## [Using Local Storage on Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

- A web application on the internet is considered stateless because it resets whenever the web application is closed and reopened
- A desktop application does not have the same issue because it will return back to it's current state when it is closed then reopened
- A cookie is a file stored on the user's computer that saves information and helps restore some data for the web application
- Access local storage through the ```localStorage``` object or call it using ```setItem()``` and ```getItem()```
- Security concerns exist regarding the storage of user data. Remember to be mindful of the types of information saved on the internet
- Local storage can only store as string data and any other types of data must first be converted to strings

### Questions

1. Why would a developer use local storage for a web application?
- For convenience to return users to a previous state in the application and to store user information for reference or future use in the application
2. What information should not be stored in local storage?
- Personal and financial information
3. Local storage can store what type of data? How would you convert it to that type before storing?
- Local storage can only store string data and can be converted using ```JSON.stringify()``` and ```JSON.parse()``` methods

## Additional Resources

## [More About Local Storage](https://diveinto.html5doctor.com/storage.html)

## Things I want to know more about

- How does an application that stores user passwords get around the security risks of storing sensitive information? Is it through encryption?
