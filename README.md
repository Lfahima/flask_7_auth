# flask_7_auth
This is assignment #7 for HHA 504 


## 1. Session Management with Flask-Session:
#### Document how you set it up and how it works in managing user sessions.
I first import session from flask. Once the user logs in I generate a token and set the sessions user to the user that logged in. 
If the user does not exist in the database I also create a user. 
When the user wants to log out I remove them from the session.

#### Highlight the benefits of using Flask-Session and any challenges encountered.
Benefits:
Tracks users throughout.
Able to handle user log in and log out. 
User does not have to log in multiple times. 
Tracks user even if they leave the application. 
No challenges encountered using flask-session.  


## 2. User Authentication with Flask:
#### Document the security precautions you've taken, such as preventing SQL injection, using secure authentication flows, and ensuring secure session management.
I am using only google as the authentication flow, which means that users cannot perform any SQL injection and because google already handles this and I do not have to worry about it. 
 

## 3. Cloud-based Authentication System:
 #### Discuss the benefits of using cloud-based identity solutions and their advantages over traditional authentication methods.



### A detailed walkthrough of my user authentication system.
I have "Sign in with google" which uses the google identity platform and the "login with google" which uses flask OAuth and google. 
I also have log-out bottons for both options. 
The login buttons also registers a new user if needed. 

### Observations on session management and cloud-based authentication.
Session management allows for more custom login (do it yourself), whereas cloud-based authentication allows it for you. 

 ### Challenges faced, measures taken to overcome them, and lessons learned.
The only challenge I faced was that I had a hard time using the google identity platform, I had to do alot of the research myself. 