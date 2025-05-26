# Devops-project
Step-1 Node.js REST API
 
 =>Step 1: Initialize the project
           npm init -y
           This creates a basic package.json.
 
 =>Step 2: Install Express
 =>Step 3: Create the app.js file
 =>Step 4: Add a start script
           Open package.json and edit the "scripts" section 
		"scripts": {
  			"start": "node app.js"
			   }
 => step-5:Test It Locally
	Run the server:
	  npm start
    visit: http://localhost:3000

 _______________________________________________________________________________________

Step-2 Docker

 =>Step 1: Initialize the project
           npm init -y
           This creates a basic package.json.
 
 =>Step 2: Install Express
 =>Step 3: Create the app.js file
 =>Step 4: Add a start script
           Open package.json and edit the "scripts" section 
		"scripts": {
  			"start": "node app.js"
			   }

 =>Step 5:docker build -t my-node-app .
	     to build 
   	  docker run -p 3000:3000 my-node-app
	     to run

 =>Visit: http://localhost:3000
