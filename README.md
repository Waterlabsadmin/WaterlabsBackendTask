# waterlabsBackendTask
# WELCOME TO WATERLABS.AI CODING CHALLENGE
## Backend-Assignment

###### THIS CHALLENGE WOULD CONSIST OF 2 TASKS

###### YOUR SOLUTION MUST BE SENT AS A GIT LINKS FROM YOUR GIT ACCOUNT

###### CREATE A GIT REPO IN YOUR PERSONAL GIT AND EACH TASK MUST BE A FOLDER IN THE GIT 

###### THE GIT REPO MUST HAVE DETAILED README FILE TO RUN SCRIPTS FOR EACH TASK

###### THE REPO MUST HAVE REQUIREMENTS REQUIRED TO RUN EACH TASK 
 
###### CODE QUALITY AND CODE COMMENTING IS MUST 


######  Once the assignment is complete, zip your code and password protect it.

###### Push the zip file to a new branch. 

###### Share the branch name and password over email.

###### THE REPO MUST HAVE REQUIREMENTS REQUIRED TO RUN EACH TASK 
 
###### Contact us in case of any queries 




### Task 1

Create a Custom User model(Feel free to give the model any name you wish) in django. The model should consists of the following fields.
	1. Username
	2. Password
	3. Email
Use ModelViewSet for all CRUD operations. At the end of the assignment we should be able to perform the CRUD operation using the URLs exposed by the service. Use a django pre save signal or a DB trigger to hash the password before saving the password
Note: Do not extend or use the default django User model. You can use a SQL DB of your choice


### Task 2

Create an endpoint called authenticate(HTTP POST request), which takes Username, Password(Plain text) as input and check if the Password saved in the DB is same as the Password passed in the request. Return a message "Passwords match" if they match and "Passwords do not match" if they do not match, with appropriate status codes.



