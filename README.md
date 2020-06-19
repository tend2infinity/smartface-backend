# SMARTFACE-BACKEND
This is the backend component of my smartface app , done with the help of "NODE.js and EXPRESS.js"
the complete server development has been done in this repository .

## SERVER DESIGN

### / --> res = this is working

This is the root route which indicates that our App is working.

### /sigin --> POST = success/fail

This is the sign in route , as clear from above that its a post request as it sends some data from the frontend to the server .

### /register --> POST = user

Quite similar to signin route .

### /profile/:userId --> GET = user

This endpoint open up when you successfully login into the App .

### /image --> PUT --> user

This end point is used for the increment of image count and also for the rank of the user .

This is a short representation of the endpoints used in this App.
