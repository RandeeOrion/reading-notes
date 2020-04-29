# Bearer Authorization

**When is Basic Authorization used vs. Bearer Authorization?**

Basic Authorization is great for setting up an account or when a user is sending their user name and password to log in. Bearer authorization is used for tokens, whether it is tokens the server generates or with oAuth. 


**What does the JSON Web Token package do?**

JSON Web Token allows developers to create encrypted tokens with ease. Making logins more secure for clients.

**What considerations should we make when creating and storing a SECRET?**

First, it needs to be kept secret, storing in an .env file is a a great way. Second, it needs to be consistent through the use of JWT. 