# Class 15 - Authentication

## [What is OAuth](https://www.csoonline.com/article/562635/what-is-oauth-how-the-open-authorization-framework-works.html)
- OAuth allows authorized users access to a server/service along with their related data and information

### Questions

1. What is OAuth?
- Safely allows authenticated access to assets 
2. Give an example of what using OAuth would look like.
- Connecting an online calendar and it's information to my personal google calendar
3. How does OAuth work? What are the steps that it takes to authenticate the user?
- Connect to website
- Somehow an exchanging of tokens occurs between a first and second website
- User is granted access to the website
4. What is OpenID?
- "OpenID is for humans logging into machines" - quoted from article that quoted StackOverflow commenter

## [Authentication and Authorization Flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)


### Questions

1. What is the difference between authorization and authentication?
- Authorization allows a user to user their data and servers whereas authentication verifies the identity of a user
2. What is Authorization Code Flow?
- User logs into application
- Directed to /authorize endpoint
- User authenticates
- Exchanging of tokens occurs
- User accesses data 
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
- User logs into application
- A code challenger is randomly created
- User authenticates
- Exchanging of tokens occurs
- User accesses data
4. What is Implicit Flow with Form Post?
- Alternative to Authorization Code Flow for Public Clients or applications unable to securely store Client Secrets
5. What is Client Credentials Flow?
- An authentication process to allow authorization for an app to connect and use data
6. What is Device Authorization Flow?
- An authentication process that directs the users to a link on their computer or smartphone to authorize the device
7. What is Resource Owner Password Flow?
- An authentication process which requests users to provide username and password

## Additional Resources

## [AuthO for Single Page Apps](https://auth0.com/docs/libraries/auth0-react)

## Things I want to know more about
- What is the purpose of exchanging tokens?
- Is this any different from those captcha authentication?
- Having a hard time grasping the difference between OpenID and OAuth