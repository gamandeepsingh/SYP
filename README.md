# SYP - Sell Your Product

SYP is a MERN stack application built with TypeScript that allows users to upload files (such as PDFs, images, zips, etc.) and specify a price for selling them. Other users can browse, purchase, and securely download these files using Razorpay as the payment gateway.

## Features

- User Authentication (Sign Up, Login, JWT-based sessions)
- Upload various file types (PDFs, images, zips, etc.)
- Add a price for each uploaded file
- Browse and purchase uploaded files
- Secure payment integration with Razorpay
- Dashboard for users to manage their uploaded files and sales
- Download access provided only to purchasers
- Responsive design with a user-friendly interface

## Tech Stack

- **Frontend**: React, TypeScript, Axios
- **Backend**: Node.js, Express, TypeScript
- **Database**: MongoDB with Mongoose
- **Payment Gateway**: Razorpay
- **Cloud Storage**: AWS S3 or Cloudinary (for file uploads)
- **Others**: Nodemon, Multer (for file uploads), bcrypt (for password hashing), JWT (for authentication)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js (v16 or later)
- MongoDB (local or MongoDB Atlas)
- A Razorpay account for payment integration

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/SYP-SellYourProduct.git
   cd SYP-SellYourProduct
   ```

2. **Install dependencies for the backend**:

  ```bash
  cd backend
  npm install
  ```

3. **Install dependencies for the frontend:**:

  ```bash
   cd ../frontend
   npm install
  ```

4. **Environment Variables:**:
  - Create a `.env` file in the `backend` directory and add the following variables:
  ```bash
  PORT=5000
  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret_key
  RAZORPAY_KEY_ID=your_razorpay_key_id
  RAZORPAY_SECRET=your_razorpay_secret
  ```

5. **Run the Development Servers:**:
  Open two terminal tabs and run:
  - Backend:
  ```bash
   cd backend
   npm run dev
  ```
  -Frontend
  ```bash 
   cd frontend
   npm run dev
  ```
  The backend server will run on `http://localhost:5000` and the frontend server will run on `http://localhost:3000`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


### Notes for Customization:
- Replace `yourusername` in the Git clone URL with your actual GitHub username.
- Add your MongoDB connection string, JWT secret key, and Razorpay keys in the `.env` file.
- Include a `LICENSE` file if you choose to use the MIT License or any other license.

This `README.md` provides a comprehensive overview of the project, guiding users through setup, installation, and usage. It also encourages contributions, making it easier for others to get involved in development.

