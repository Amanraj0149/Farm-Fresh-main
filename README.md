# 🌾 FarmFresh Marketplace 🌾

Welcome to **FarmFresh Marketplace** - a platform designed to connect farmers and local sellers with customers seeking fresh, raw materials and crops! Built with the **MERN Stack** (MongoDB, Express, React, Node.js), this full-stack marketplace provides a seamless buying and selling experience.  

### 🌐 Live Demo
You can view the project live at [farmfreshmernstack.netlify.app](https://farmfreshmernstack.netlify.app/)

---

## 📜 Key Features

- **Admin Panel**: Comprehensive control for product and order management.
- **User Authentication**: Secure login and registration with **JWT** for token-based authentication and **bcrypt.js** for password encryption.
- **Payment Integration**: Secure payments powered by **Stripe API**.

---

## 🚀 Getting Started

### Prerequisites
Before installing, ensure you have **Node.js**, **MongoDB**, and **npm** (Node Package Manager) installed on your machine.

### Installation

To get started, clone the repository and navigate to the project folder. You’ll need to install dependencies separately for the backend (server) and frontend (client).

1. **Clone the Repository**: Clone the repository to your local machine and navigate into the project directory.

2. **Install Dependencies**:
   - For the server, navigate to the `server` folder and run `npm install` to install backend dependencies.
   - For the client, go to the `client` folder and run `npm install` to install frontend dependencies.

3. **Configure Environment Variables**: In the `server` folder, create a `.env` file to set up essential environment variables. These variables typically include:
   - `PORT` (the port your server will run on, e.g., 5000),
   - `MONGO_URI` (your MongoDB connection string),
   - `JWT_SECRET` (a secret key for JWT authentication),
   - `STRIPE_SECRET_KEY` (your Stripe API secret key for payment processing).

4. **Run the Application**:
   - To start the server, navigate to the `server` folder and use the `npm run dev` command, which will launch the backend server on your specified port.
   - To start the client, go to the `client` folder and use the `npm start` command. By default, the client runs on `http://localhost:3000`.

Once these steps are completed, you should have the full application running locally, with the frontend accessible on `http://localhost:3000`.

---

## 🛠️ Technologies Used

- **Frontend**: React.js, Redux for state management
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT) with bcrypt.js
- **Payments**: Stripe API

---

## 📸 Screenshots

| Home Page                           | Admin Panel                        |
|-------------------------------------|------------------------------------|
| ![Home Page](screenshot1.png)       | ![Admin Panel](screenshot2.png)    |

---

## 📚 Documentation

### API Endpoints Overview

- **Login**: `/api/auth/login` (POST) - Authenticates a user and provides a token.
- **Register**: `/api/auth/register` (POST) - Registers a new user with encrypted password.
- **Fetch Products**: `/api/products` (GET) - Retrieves all available products.
- **Create Order**: `/api/orders` (POST) - Creates a new order.
- **Admin Functions**: `/api/admin` (GET) - Accesses admin functionalities for managing products and orders.

### Environment Variable Setup

An example `.env` file for the server might look like this:
- `PORT=5000`
- `MONGO_URI=your_mongo_db_uri`
- `JWT_SECRET=your_jwt_secret`
- `STRIPE_SECRET_KEY=your_stripe_secret_key`

---

## 👤 Author

**Aman Raj** – You can connect with me on GitHub at [https://github.com/your-username](https://github.com/your-username).

---

## 👥 Contributors

- **Backend & Deployment**: Aman Raj
- **Frontend**: Ritesh Verma, Rohan Gon

---

## 💡 Future Enhancements

- **Expanded Product Categories**: Introduce more categories to diversify offerings.
- **Improved Mobile Responsiveness**: Optimize the UI for a seamless mobile experience.
- **Multilingual Support**: Add support for multiple languages to reach a broader audience.

---

Thank you for visiting **FarmFresh Marketplace**!
