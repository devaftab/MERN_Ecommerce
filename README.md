# MERN E-commerce Application

A comprehensive e-commerce platform built using the MERN stack (MongoDB, Express, React, Node.js). This project includes features like product listing, user authentication, shopping cart, and order management, offering a seamless shopping experience.

## 🚀 Features

- **User Authentication**: Secure login and registration with JWT-based authentication.
- **Product Management**: CRUD operations for products, with search and filter options.
- **Shopping Cart**: Add, update, and remove products from the cart.
- **Order Management**: Place orders, track delivery status, and manage order history.
- **Payment Integration**: Integrated payment gateway for processing transactions.
- **Admin Dashboard**: Manage users, products, and orders with dedicated admin privileges.

## 🛠️ Technology Stack

- **Frontend**: React.js, Redux for state management, Bootstrap for responsive UI.
- **Backend**: Node.js, Express.js for API endpoints and server logic.
- **Database**: MongoDB for storing user, product, and order data.
- **Authentication**: JWT-based authentication and authorization.
- **Deployment**: Deployed on Render or another cloud service provider.

## 🔧 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/devaftab/MERN_Ecommerce.git
   cd MERN_Ecommerce
   ```

2. Install dependencies for both the backend and frontend:

   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. Create a `.env` file in the backend directory with the following environment variables:
   
   ```plaintext
   PORT = 4000
   NODE_ENV = Development
   
   MONGO_URL=<Your MongoDB URI>
   JWT_SECRET_KEY=<Your JWT Secret>
   JWT_EXPIRES = 7d
   COOKIE_EXPIRE = 7
   
   CLOUDINARY_NAME = <Your clodinary name>
   CLOUDINARY_API_KEY = <Your Cloudinary API Key>
   CLOUDINARY_SECRET_KEY = <Your Cloudinary Secret Key>
   
   STRIPE_SECRET_KEY = <Stripe Id>
   STRIPE_API_KEY = <Stripe API>
   
   SMPT_HOST = smtp.mailtrap.io
   SMPT_PORT = 2525
   SMPT_MAIL = smpt_mail_id
   SMPT_PASSWORD = smpt_password
   SMPT_MAIL_FROM = your_mail
   SMPT_MAIL_NAME = your_name
   ```

4. Start the backend server:

   ```bash
   cd backend
   npm run dev
   ```

5. Start the frontend server:

   ```bash
   cd frontend
   npm start
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## 📸 Screenshots

Include screenshots of different parts of the application (e.g., homepage, product page, cart, and admin dashboard) for better visualization.

## 🌐 Live Demo

Check out the live demo [here](https://onlineshop-wicb.onrender.com/).

## 🤝 Contribution

Feel free to fork this repository and submit pull requests with improvements. For major changes, please open an issue first to discuss what you'd like to change.

## 📧 Contact
If you have any questions or would like to collaborate, feel free to reach out to me:<br/><br/>
  [![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:web.dev.aftab@gamil.com)<br/>
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/devaftab/) <br/>
  
  [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/devaftab/)
