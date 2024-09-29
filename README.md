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
   MONGO_URI=<Your MongoDB URI>
   JWT_SECRET=<Your JWT Secret>
   PAYPAL_CLIENT_ID=<Your PayPal Client ID>
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

Check out the live demo [here](https://onlineshop-wicb.onrender.com).

## 📄 License

This project is licensed under the MIT License.

## 🤝 Contribution

Feel free to fork this repository and submit pull requests with improvements. For major changes, please open an issue first to discuss what you'd like to change.

## 📧 Contact

For any questions or suggestions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/devaftab) or email at web.dev.aftab@gmail.com.
