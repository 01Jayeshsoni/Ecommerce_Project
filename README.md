# Ecommerce App

The Ecommerce App is a web application that provides users with an online shopping experience. It is built using React.js for the frontend and Node.js for the backend. The app allows users to browse and purchase products from various categories.

## Features

- **User Registration and Authentication**: Users can create an account, log in, and securely authenticate themselves to access the shopping features.
- **Product Catalog**: The app displays a catalog of products, including details such as name, description, price, and availability.
- **Product Search and Filtering**: Users can search for specific products by name, category, or other attributes. They can also apply filters to narrow down the search results.
- **Product Details**: Users can view detailed information about each product, including images, specifications, and customer reviews.
- **Shopping Cart**: Users can add products to their shopping cart, modify quantities, and proceed to checkout.
- **Order Placement and Payment**: Users can place orders and make payments using various payment methods.
- **Order History**: Users can view their order history, including past orders, payment details, and delivery status.
- **User Reviews and Ratings**: Users can provide feedback by writing reviews and rating products they have purchased.
- **Admin Dashboard**: An admin panel allows administrators to manage products, categories, user accounts, and orders.

## Installation and Setup

### Prerequisites

- Node.js and npm (Node Package Manager) should be installed on your machine.
- MongoDB should be installed and running.

### Frontend Setup

1. Clone the repository:

   ```shell
   git clone https://github.com/01Jayeshsoni/Ecommerce_Project.git
   ```

2. Navigate to the frontend directory:

   ```shell
   cd Ecommerce_Project/frontend
   ```

3. Install the dependencies:

   ```shell
   npm install
   ```

4. Start the frontend development server:

   ```shell
   npm start
   ```

   The frontend application will be accessible at `http://localhost:3000`.

### Backend Setup

1. Navigate to the backend directory:

   ```shell
   cd Ecommerce_Project/backend
   ```

2. Install the dependencies:

   ```shell
   npm install
   ```

3. Set up the environment variables:
   - Create a `.env` file in the backend directory.
   - Add the following environment variables to the `.env` file:
     - `MONGODB_URI`: MongoDB connection URI.
     - `JWT_SECRET`: Secret key for JWT authentication.

4. Start the backend server:

   ```shell
   npm start
   ```

   The backend server will be accessible at `http://localhost:5000`.

## Contributing

Contributions to the Ecommerce App are welcome! If you find any bugs, have suggestions for improvements, or would like to contribute new features, please feel free to submit an issue or create a pull request.

## License

The Ecommerce App is open source and distributed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

If you have any questions or inquiries, please contact [your-email@example.com](mailto:your-email@example.com).

## Acknowledgements

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
