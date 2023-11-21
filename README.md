#Messaging App

Welcome to the Messaging App repository! This project is a full-stack messaging web application built with Node.js, React, and Tailwind CSS. Below is an overview of the development process and instructions to get the application up and running.



Integrated React and Tailwind CSS for a modern and responsive user interface.


Implemented user authentication with login and registration functionality.


Created a dynamic chat page where users can interact and exchange messages.


Implemented Websockets for real-time updates, ensuring secure user authentication.


Enhanced user profiles with avatar support for a personalized experience.


Implemented the ability for users to select and view different conversations.


Enabled users to send messages with a user-friendly interface.


Implemented automatic scrolling for a seamless conversation experience.


Integrated database functionality to fetch and display message history.

Ensured automatic re-connection for a consistent user experience.


Implemented the display of messages retrieved from the database.


Added online indicators and the ability to view offline users.


Implemented a mechanism to terminate outdated connections for efficiency.


Added a logout button and displayed the username of the currently logged-in user.


Implemented attachment functionality for file uploads.


Addressed and fixed a minor display bug for a polished user interface.


#Tech Stack

The following technologies were utilized in building this application:

Backend (Node.js):

RESTful APIs for user authentication and messaging operations.
Frontend (React):

Components for login, registration, chat interface, and more.
Styling (Tailwind CSS):

Responsive and customizable styling for a modern UI.
Websockets:

Implemented for real-time updates and secure authentication.



cd messaging-app
yarn install

Start the server:

yarn start
The server will run at http://localhost:4040 by default.

Run the frontend:

cd frontend
yarn install
yarn start
The frontend will open in your web browser, and you can start testing the application.
