## Pinterest Clone
### Description
This project is an attempt to clone the Pinterest website, offering similar functionalities and user experience.

## Routes
### User Routes
	- POST /register
	Description: Creates a new User.
	Input Body: {  name,  email,  password  }
	Output: { message: "User Registered" }
	
	- POST /login
	Description: Login.
	Input Body: { email,  password  }
	Output: { message: "Login Successfully" }
	
	- POST /logout
	Description: Logout a User.
	Output: { message: "Logout" }
	
	- GET /me
	Description: Get all the users.
	Output: Users array
	
	- GET /:id
	Description: Get User By Id.
	Output: User
	
	- GET /follow/:id
	Description: Follow and Unfollow Someone
	Output: Update the count of follower.

### Pins
	- POST  /new
	Description: Creates a new Pin.
	Input Body: {  name,  des,  image  }
	Output: { message: "New Pin Created" }
	
	- POST  /comment/:id
	Description: Creates a new Comment.
	Input Body: {  id,  name,  comment  }
	Output: Comment added
	
	- GET /all
	Description: Creates a new User.
	Input Body: {  name,  email,  password  }
	Output: { message: "User Registered" }
	
	- GET /:id
	Description: Get a Single Pin.
	Output: Image
	
	- PUT /:id
	Description: Update a Pin.
	Input Body: {  title,  des  }
	Output: Update the pin
	
	- DELETE /:id
	Description: Delete the Pin
	Output: Pin deleted
