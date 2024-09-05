# Name of Project - Raider Social


## Elevator Pitch
- Raider Social will be a way for Wright State students to connect and communinicate with each other. Raider Social will be exclusive to just Wright State students.

## N things of complexity (componets)
- UI Design
  - Creating a appealing and user friendly interface
- Backend
  - Writing the business logic and communicating with the database
- Data Storage
  - Persistent storage for user and app data
- Deployment
  - Deploying to GoDaddy
- Testing
  - Testing the whole system to ensure functionality 
  
## What language or technology stack or framework will be used (Why as well)?

- Flutter (Dart)
  - We will be using Flutter as a framework and Dart programming language to create Mobile Application for the UI portion of the system. We have chosen Flutter because it is cross platform framework and will allow us to create both iOS and Andriod application at the same time. Since the time constraints and developers of this project is limited, we have have choosen Flutter to better use our time and team members more efficiently.

- Express
  We will be using Express framework and Javascript programming language to create the Server of our system. We have selected Express framework to create the server of our system because the developer community of Express is extremely huge and it the most widely used framework for backend developement in this day and age. Due to its mass adoption we are hopeful that any hinderances that we might face during the developement process will be quickly and easily resolved.

- PostgreSQL
  We are opting to use PostgreSQL as our datebase of choise. PostgreSQL is also a widely used RDBMS and will give us the oppertunity to work with and learn SQL language whilst we create the database of of our system.

- GoDaddy
  We will use GoDaddy to host our Server. GoDaddy is free to use and is relatively less complex compared to other alternatives such as AWS. Hosting in GoDaddt is realatively and easier process and since none of our team memners are well versed in deployment of Servers we are using GoDaddy as a safe bet for now.

## How do the components fit together (i.e., predicted architecture)?

  The system is going to be a Client - Server Architecture. 

  The Mobile application (Client) availabe in both iOS and Android devices are going to be the User Interface for the end users, where they get to login and communicate with other Wright State unversity students. Whenever the end user wants access or manipulate some data regarding the current user, other users on the portal or any other system data, the Mobile Application is then going to communicate with the Backend (Server).

  The Backend (Server) of the system is going to accept HTTP requests from the Client (Mobile Application) and send back a response to the client accordingly. It will be the backends job to authenticate the user and also to perform any Business Logic that is required. When the backend receives any request it is going to get the data stored in the Database, perform any Business Logic (if necessary) and then send the response back to the client.

  The Database is goint to store all the data of the system. The details of the users, other system information, authentication information is going to be stored in the Database in rows much like that of an excel sheet. The Server will query the Database to get back any data that is required.

  Lastly, the Server will be deployed on GoDaddy so that any user that has access to the internet can access our system.

## What is the predicted life cycle/methodology that you will follow
