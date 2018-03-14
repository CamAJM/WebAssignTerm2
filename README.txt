Step 1:
Extract the zip

Step 2:
Node modules are included but can be updated

Step 3:
Ensure MongoD is running

Step 4:
From the main directory (mongoDB), run "node app.js"

Step 5:
Using the mongo client, create a new admin user using the code below.

Step 6:
Connect to http://localhost:3000

Step 7:
Login in using one of the login details below.


Assumptions:

An admin will be added through the MongoDb while downloading. 

Mongo code for this:

db.myusers.insert(
[
	{
		username: "adminUser",
		password: "userAdmin",
		firstname: "Admin",
		lastname: "User",
		position: "Admin"

	},
	{
		username: "Customer001",
		password: "firstCustomer",
		firstname: "Customer",
		lastname: "001",
		position: "Customer"
	},
	{
		username: "Staff",
		password: "firstMember",
		firstname: "Staff",
		lastname: "001",
		position: "Staff"
	},
]
)




Notes:

Screenshots are provided as was requested in assignment brief.

Bills are auto-added by the waiter
