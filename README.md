# flask_7_auth
This is assignment #7 for HHA 504 


1. Session Management with Flask-Session:
- Document how you set it up and how it works in managing user sessions.
I frst impirt session from flask. once the user logs in i generatea token and set the sessions uswer to the user that logged in. 
if the user does not exist in the database i also vreate a user. 
when the user wants to log out i remove them from the session.

- Highlight the benefits of using Flask-Session and any challenges encountered.
benefits:
track user throughout life scysle of application.
handle user loging and log out 
user does not have to log in multiple times 
track user even if they leave the application 
no challeneged with the flask session 

- Document the security precautions you've taken, such as preventing SQL injection, using secure authentication flows, and ensuring secure session management.
I am using a only google as the autenticaiton flow which means that users cannot perform any sql injection and because google already handles this i do not have to worry baot it. 
 

 - Discuss the benefits of using cloud-based identity solutions and their advantages over traditional authentication methods.

- A detailed walkthrough of your user authentication system.
I HAVE SIGN IN WITH GOOGLE WICH uses THE GOOGLE IDENTIFY PLATFORM and the login with google which uses flask oauth and google. 
i also have logout botton for botton for both options 
the login buttons also registers a new user if needed. 

- Observations on session management and cloud-based authentication.
sesion mnag aloows for more custom login (do it your self) whereas cloud based uath aloows it for you 

 - Challenges faced, measures taken to overcome them, and lessons learned.
the only chALLge i had a hard time using the google idenytity platform , i had to do research myself and the documentaiton is all over the place. 
there is no good documentation for python so i am using html and java script to use the google odentity platform. 