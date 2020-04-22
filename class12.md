# O Auth

**What’s a benefit of using OAuth instead of your own basic authentication?**
OAuth allows for additional information to be collected, like full name, email, cellphone number, etc without you having to provide it. Sorted of a local cached info access card. 

**Write the following steps in the correct order:**
- Ask the client if they want to sign in via a third party
- Redirect to a third party authentication endpoint
- Make a request to a third-party API endpoint
- Make a request to the access token endpoint
- Receive access token
- Receive authorization code
- Register your application to get a client_id and client_secret


**What can you do with an authorization code?**
- An authorization code is simply for the server to read info from the user. 

**What can you do with an access token?**
- An access token allows that particular user to have access to whatever information those types of token holders are allowed access to. Its like the TSA preapproval. 