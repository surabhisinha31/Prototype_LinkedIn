# Prototype_LinkedIn

submitted by: surabhi sinha(surabhi.sinha@sjsu.edu)

Project Description Through this project, I have designed a web application with RESTful API that simulates Linkedin website using react and redux for Frontend and node js for Backend and Kafka for message queuing.

•	The LinkedIn simulator that I have built and implemented is an application that imitates basic features and services provided by the Linkedin application.

•	The application allows the users to login as a simple user or as a recruiter. 

• The recruiter will post the job same as in actual LinkedIn application.

•	The users can search for the jobs posted by the recruiters based on the job title , location .

• The Jobs has two categories as in original Linkedin : "Easy Apply" and "Apply". User can apply to jobs through any of the types of these jobs.

• The user can update his profile information , his profile pic and all the details he could update in original LinkedIn.

• The user can chat with other users as well as recruiter.

• The user can send and accept connections to other users and the recruiters.

• The user can view a bar chart representing how many people has visited his profile in the last 6 months.

• The recruiter has a dashboard where in he can get informations regarding jobs posted by him. E.g : No. of applicants who have saved
that job, no. of applicants half filled the jobs, no. of applicants filled the job.

• The recruiter can view a pie chart for the no.of applicantions from each city he posted job for in last 3 months.

• The project includes 7 charts to give better understanding to recruiters and users about the jobs posted and the profile info.

# Setup & Run To run the application fork and clone the repository, 
# backend setups
cd into the linkedin-backend directory, then run the following commands to setup & start the server:

$ npm install  : install required libraries

$ npm start  : start the backend server on port 3001

cd into the kaka_backend directory, then run the following commands to setup & start the server:

$ npm install : install required libraries

$ npm start : start the kafka

# frontend setups
cd into the linkedin-frontend directory, then run the following commands to setup & start the server:

$ npm install  : install required libraries

$ npm start # start the server on port 3000

Once the server is running, you should be able to access the app at http://localhost:3000.
