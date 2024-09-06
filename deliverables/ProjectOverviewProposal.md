# Name of Project - Raider Social


## Elevator Pitch
- Raider Social will be a way for Wright State students to connect and communicate with each other. Raider Social will be exclusive to just Wright State students.

## N things of complexity (components)

- UI Design
  - Creating a Interface that is both appealing to look at and easy to use for the end user. We will be creating cross platform (works on both Android and iOS) Mobile Application for the Frontend portion of our system.

- Backend
  - We will create a Server for our Frontend to communicate with. The Server will query the Database to fetch all the data that is required for our users to interact with the system.

- Data Storage
  - We will setup a Database using PostgreSQL to persistently store all of the data that our system utilizes, including the user data and other system data as well.

- Deployment
  - The server will be hosted on the Internet so that any user with the access to the Internet can have access to our system. We will be using a hosting service such as GoDaddy to host our server.

- Testing
  - The whole system is going to be thoroughly tested for its functionality, implementation and to reduce the amount of Bugs so that our Raiders can have a smooth and bug free experience whist using our application.
  
## What language or technology stack or framework will be used (Why as well)?

- Flutter (Dart) :
  We will be using Flutter as a framework and Dart programming language to create Mobile Application for the UI portion of the system. We have chosen Flutter because it is cross platform framework and will allow us to create both iOS and Android application at the same time. Since the time constraints and developers of this project is limited, we have have chosen Flutter to better use our time and team members more efficiently.

- Express :
We will be using Express framework and Javascript programming language to create the Server of our system. We have selected Express framework to create the server of our system because the developer community of Express is extremely huge and it the most widely used framework for backend development in this day and age. Due to its mass adoption we are hopeful that any hindrances that we might face during the development process will be quickly and easily resolved.

- PostgreSQL :
  We are opting to use PostgreSQL as our database of choice. PostgreSQL is also a widely used RDBMS and will give us the opportunity to work with and learn SQL language whilst we create the database of of our system.

- GoDaddy :
  We will use GoDaddy to host our Server. GoDaddy is free to use and is relatively less complex compared to other alternatives such as AWS. Hosting in GoDaddy is relatively and easier process and since none of our team members are well versed in deployment of Servers we are using GoDaddy as a safe bet for now.

## How do the components fit together (i.e., predicted architecture)?

  The system is going to be a Client - Server Architecture. 

  The Mobile application (Client) available in both iOS and Android devices are going to be the User Interface for the end users, where they get to login and communicate with other Wright State university students. Whenever the end user wants access or manipulate some data regarding the current user, other users on the portal or any other system data, the Mobile Application is then going to communicate with the Backend (Server).

  The Backend (Server) of the system is going to accept HTTP requests from the Client (Mobile Application) and send back a response to the client accordingly. It will be the backends job to authenticate the user and also to perform any Business Logic that is required. When the backend receives any request it is going to get the data stored in the Database, perform any Business Logic (if necessary) and then send the response back to the client.

  The Database is going to store all the data of the system. The details of the users, other system information, authentication information is going to be stored in the Database in rows much like that of an excel sheet. The Server will query the Database to get back any data that is required.

  Lastly, the Server will be deployed on GoDaddy so that any user that has access to the internet can access our system.

## What is the predicted life cycle/methodology that you will follow

  We will be working according to Agile Methodology because it will allow us to break up the project in multiple phases and ensure that we will be able to deliver at least the Minimal Viable Product in the given constrained time frame.

  Scrum:
  We will specifically be following Scrum framework in this project. We are planning on making the Sprints two weeks long.

## Signatures

  Dipesh Paneru, Hayden Troxell, Tyler Wells, Adam LaDue
