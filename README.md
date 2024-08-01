# E-commerce Platform

## Description
A full-featured e-commerce platform built with React, Redux, Node.js, Express, and MongoDB.

## Features
- User authentication with JWT
- Product listing and details
- Shopping cart functionality
- Order placement and payment processing
- Admin panel for product management

## Installation

### Backend
1. Clone the repository: `git clone https://github.com/your-repo/ecommerce-platform.git`
2. Navigate to the backend directory: `cd ecommerce-platform/backend`
3. Install dependencies: `npm install`
4. Create a `.env` file in the backend directory with the following:

**MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret** -->
5. Start the server: `npm start`

### Frontend
1. Navigate to the frontend directory: `cd ecommerce-platform/frontend`
2. Install dependencies: `npm install`
3. Create a `.env` file in the frontend directory with the following:

REACT_APP_API_URL=http://localhost:5000/api:
4. Start the frontend server: `npm start`

## Usage
1. Register or login as a user.
2. Browse products, add them to the cart, and proceed to checkout.
3. As an admin, you can manage products from the admin panel.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
