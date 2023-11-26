# Skillify
Description
Skillify is an online learning platform that delivers educational courses over the internet. The main purpose of e-learning apps is to facilitate teaching adn learning anytime, anywhere through digital devices.

Tech Stack Used
Frontend: React, Recoil, RTK Query, Tailwind CSS

Backend: Node.js, Express.js, MongoDB, JSON Web Tokens (JWT) for authentication

Others: react-icons, Sonner

Installation
Follow these steps to set up the ToDo App on your local environment:

Clone the Repository:

git clone https://github.com/sarveshdutt17feb/skillify.git

cd DevSikShaHub
Backend Setup:

Navigate to the Server directory:

cd Server
Install the required dependencies:

npm install
Configure the environment variables:

Create a .env file in the backend directory.

Define the following variables:

PORT= 3000
DATABASE_URL=<your-database-url
SECRET_KEY=<your-secret-key>
Start the backend server:

npm start
Frontend Setup:

Navigate to the Client directory:

cd Client
Install the required dependencies:

npm install
Start the frontend application:

npm run dev
Access the App:

Open a web browser and go to http://localhost:5173 to access the Do_IT App.
Features
Admin/User signup and login
Free access to roadmaps and free videos
Admin/User can update their profiles, delete their accounts after succesfull login
Admin can create, update , delete their respective courses.
User can add his favourite course to the cart and purchase it and has access to his respective dashboard
Great UI and dark,light modes for great user experience
Future Work
Admin/User can upload their profile picture
Admin can add courses( videos, pdfs) to the course content
User can purchase the course (payment method integration) and can see the content of the admin
User can give feedback to the admin to his purchased courses
OAuth integration
