# MERN E-Commerce Website

![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Welcome to the MERN E-Commerce Website project! This is a full-stack e-commerce application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application provides a robust platform for users to browse products, add them to their cart, and proceed with purchasing.

## Features

- User authentication and authorization
- Product listing and detailed views
- Shopping cart functionality
- Order processing
- Admin dashboard for managing products and orders
- Responsive design for mobile and desktop

## Technologies Used

- **Frontend:** React.js, Redux, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Payment Gateway:** Stripe

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
    ```
    git clone https://github.com/anjangujjar/MERN-ECOMERCE-WEBSITE.git
    cd MERN-ECOMERCE-WEBSITE
    ```

2. **Install dependencies for both frontend and backend:**
    ```
    # Install backend dependencies
    cd server
    npm install

    # Install frontend dependencies
    cd ../client
    npm install
    ```

3. **Set up environment variables:**
    Modify the `index.js` file in the `server` directory with the following content:
    ```
    NODE_ENV=development
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```

4. **Run the application:**
    ```
    # Run backend
    cd server
    npm run dev

    # Run frontend
    cd ../client
    npm start
    ```

## Usage

Once the application is up and running, you can access it at `http://localhost:3000`. You can register a new account, browse products, add them to your cart, and proceed with the checkout process.

To access the admin dashboard, you need to log in with an admin account. The admin dashboard allows you to manage products and orders.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
    ```
    git checkout -b feature-name
    ```
3. Make your changes and commit them.
    ```
    git commit -m "Description of your changes"
    ```
4. Push your changes to your forked repository.
    ```
    git push origin feature-name
    ```
5. Open a pull request on the original repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions, feel free to reach out to me:

- **GitHub:** [anjangujjar](https://github.com/anjangujjar)
- **Email:** [anjangujjar1310@gmail.com](mailto:anjangujjar1310@gmail.com)

---

Thank you for checking out the MERN E-Commerce Website project! Your support and contributions are greatly appreciated.
