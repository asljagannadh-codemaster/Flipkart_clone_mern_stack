![{9D45E0ED-6209-4FFD-BFD6-4D2A0D9BEDF0} -pxbee-minitools-enhance-20250903205806](https://github.com/user-attachments/assets/b118c820-718b-4a7d-ade6-c8ea08cf1f40)Project Overview:

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
The Home Page is as below:
<img width="1920" height="1080" alt="flipkart___" src="https://github.com/user-attachments/assets/693ec0c3-911b-4633-bcb1-740d35ae8d93" />

After Clicking the sign in the complete interface will be as below:
<img width="1801" height="874" alt="flipkart___1" src="https://github.com/user-attachments/assets/f107190c-45b5-43f9-83d6-2dcde782a0f7" />
If we can also login via mobile number: 
![{8C3E8179-1229-490A-B06D-ADA7D10C8BC0} -pxbee-minitools-enhance-20250903195221](https://github.com/user-attachments/assets/d5ef2978-f0ac-4a49-9314-12e6e9d80822)
We can Keep some into the cart also, whose interface is as given below:
![{E21C2A38-8632-4BF7-B650-25ECBE22E4D6} -pxbee-minitools-enhance-20250903204945](https://github.com/user-attachments/assets/95afcdf3-9d56-47c1-b08f-1cd60abe6d52)
After the click payment, we can get into the Paytm gateway, which I am using with the help of the paythm API. Whose interface is as given below:
![{A21872AF-2337-48AE-949A-492A72CF00FB} -pxbee-minitools-enhance-20250903205353](https://github.com/user-attachments/assets/37b90519-529b-4e66-8b1d-ca92a35fde62)

A small catalog of products is added to make it similar to the catalogs, which will be repeated again and again. As in the below figure:
![{E815778F-BA70-483D-A74D-F21A383D5C7C} -pxbee-minitools-enhance-20250903205607](https://github.com/user-attachments/assets/b8455574-10b4-42d7-8e1e-6759aed378fe)

When we clicked on an individual product then we will get the following kind of interface:
![{9D45E0ED-6209-4FFD-BFD6-4D2A0D9BEDF0} -pxbee-minitools-enhance-20250903205806](https://github.com/user-attachments/assets/d9811e1d-95ad-4cff-9e2e-3f5e0fc9287d)

So, these are all the main features of the projet. 

