1. What’s a benefit of using OAuth instead of your own basic authentication?
- OAuth is an open standard for access delegation and standardizes how web apps can share users data without sharing user passwords. Using OAuth saves you the time of building your own authentication nuances and also lets users login to your services without creating new passwords and whatnot.
2. Write the following steps in the correct order:
* Ask the client if they want to sign in via a third party
* Redirect to a third party authentication endpoint
* Make a request to a third-party API endpoint
* Make a request to the access token endpoint
* Receive access token
* Receive authorization code
* Register your application to get a client_id and client_secret
3. What can you do with an authorization code?
- The authorization code tells us that the client/user has allowed the server to read data from the user's Google account.
4. What can you do with an access token?
- An access token signifies that you are a "signed in user" with all the access that those users would have. 
