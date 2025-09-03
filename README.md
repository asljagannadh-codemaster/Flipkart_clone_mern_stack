Project Overview:

This project is a clone of Flipkart, a popular e-commerce platform, built using the MERN stack. It combines frontend and backend functionalities into a cohesive application.

Key Technologies Used:
React.js, Material-UI, Redux, Node.js, Express.js, MongoDB, Paytm. 
Features:

- Home Page: Displays a list of products fetched from the backend.
- Product Detail Page: Shows detailed information about selected products.
- Cart: Allows users to manage their shopping cart, adjust quantities, and proceed to checkout via Paytm.
- Responsive Design: Ensures the application is accessible and functional on various devices.

The Flipkart Clone project is a comprehensive e-commerce application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It aims to replicate the functionality and user experience of the popular e-commerce platform Flipkart, incorporating essential features and technologies for a seamless shopping experience.

For running from the github, please follow all these steps:

Go to the frontend directory:
cd flipkart-clone/client npm install

Go to the backend directory
cd ../server npm install Configure the Project Configure MongoDB:

Set up a MongoDB database. Update the connection string in server/.env with your MongoDB connection details. Configure Razor Pay:

Obtain API keys from Razor Pay. Update the API keys in the appropriate files in the project. JWT Secret:

Set a strong secret key for JWT in server/.env. Start the Application Start the Backend Server:

Copy code

Go to the backend directory

cd server npm start Start the Frontend Application:

Copy code
Go to the frontend directory

cd client npm start
Visit http://localhost:3000 in your web browser to access the Flipkart Clone application.

Then the following:

Get a free API Key at Razor Pay.
Clone this repo
Install NPM packages

npm install

Enter your API in .env

const RAZOR_PAY_API_KEY = 'ENTER YOUR API';
const RAZOR_PAY_API_SECRET;
const REFRESH_SECRET_KEY;
const ACCESS_SECRET_KEY;

Demo of my project as follows:
<img width="1920" height="1080" alt="flipkart___" src="https://github.com/user-attachments/assets/693ec0c3-911b-4633-bcb1-740d35ae8d93" />
<img width="1801" height="874" alt="flipkart___1" src="https://github.com/user-attachments/assets/f107190c-45b5-43f9-83d6-2dcde782a0f7" />


