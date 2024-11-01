# Runes Bridge

This is a Bridge between Thor chain & Ethereum.

You may checkout the project at https://runes-bridge-v2.vercel.app

Server is deployed on render so kindly wait atleast a minute for server to get deployed

## Features

- Animated landing page
- Thor & Ethereum Bridge for users
- CMS system for managing content
- Stores data in MongoDB using Mongoose
- Cloudinary integration for file uploads

## Prerequisites

Before running the project, ensure that you have the following:

- Node.js installed (version 18.X.X or higher)
- MongoDB instance (Atlas or local)
- Cloudinary account for file storage

## Project Structure

The project is organized into two main folders:

- **Client**: Contains the React.js front-end application that interacts with the server.
- **Server**: Contains the Express.js back-end application that handles API requests, user authentication, and database management.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/kjsingh03/runes-bridge.git
```

### 2. Navigate to Project Directory

```bash
cd runes-bridge
```

### 3. Client Setup

Navigate to the client folder and install dependencies:

```bash
cd client
npm install
```

### 4. Server Setup

Navigate to the server folder and install dependencies:

```bash
cd ../server
npm install
```

### 5. Environment Variables

Create a .env file in both client and server directories with the following environment variables:

#### Client .env:
```plaintext
VITE_TINY_API_KEY=xb36fw4nwp4l4pmr37pwrofwezazxwk9cu0rre5p38kh1qsf
VITE_PASSWORD=admin@999
VITE_USERNAME=admin
VITE_SERVER_URL=http://localhost:8000
VITE_CLOUDINARY_UPLOAD_PRESET=nika_v3
VITE_CLOUDINARY_CLOUD_NAME=dser8edfz
```

#### Server .env:
```plaintext
MONGODB_URI=mongodb+srv://karan:1234@cluster0.lgvyn.mongodb.net/runes?retryWrites=true&w=majority&appName=Cluster0
PORT=8000
```

### 6. Run the Project

#### Client
Start the client development server:

```bash
npm run dev
```

#### Server
Start the server:

```bash
npm start
```

The project will be available at http://localhost:5173 for the client, and the server will run on http://localhost:8000.

## License

This project is licensed under the ISC License.

## Author

Karanjot Singh  
k.jsingh.12003@gmail.com  
[GitHub](https://github.com/kjsingh03)
