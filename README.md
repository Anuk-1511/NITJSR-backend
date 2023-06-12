# College Placement Backend Site

This is the backend site for the college placement system, which allows TNP (Training and Placement) staff to add students, their scores, and manage interviews and reports. The site is built using EJS as the templating engine, Node.js as the runtime environment, and MongoDB as the database.

## Getting Started

To get started with the backend site, follow the instructions below:

### Prerequisites

- Node.js installed on your machine. You can download it from the official website: [Node.js](https://nodejs.org)
- MongoDB Atlas account. You can create one at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas). Register yourself on Mongo db atlas and use your URI for connection.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/college-placement-backend.git
   
2. Change into the project directory:
    ```bash
   cd NITJSR-backend
4. Install the dependencies:
    ```bash
   npm install
6. Set up the environment variables:
   - Create a .env file in the project root directory.
   - Add the following variables and provide appropriate values:
    ```bash
    PORT=8080
    MONGODB_URI=YOUR_MONGODB_URI
   
  Note: Replace YOUR_MONGODB_URI with the MongoDB connection URI obtained from MongoDB Atlas.
  
### Running the Server

1. Start the server:
    ```bash
   npm start
3. The backend site will be available at http://localhost:8080.

### Project Structure
  ```bash
   ├── config            # Contains databse connection
   ├── controllers       # Contains route handlers and business logic
   ├── models            # Defines the data models using Mongoose
   ├── public            # Static files (CSS, JS, images)
   ├── routes            # Defines the API routes
   ├── views             # EJS templates for rendering HTML
   ├── index.js          # Entry point of the application
   └── .env              # Environment variables
   ```



## Deployment

The backend site is deployed on Render.com. Follow the instructions below to deploy the site on Render.com:

1. Sign up for an account on [Render.com](https://render.com) if you don't have one.

2. Click on "Create a new service" on the Render dashboard.

3. Select "Web Service" as the service type.

4. Connect your GitHub repository that contains the backend site.

5. Configure the following settings for the deployment:

   - **Build Command**: `npm install`

   - **Start Command**: `npm start`

6. Click on "Create Web Service" to start the deployment.

7. Render will automatically build and deploy your backend site. Once the deployment is complete, you will be provided with a unique URL for your backend site.

8. Access your deployed backend site by visiting the provided URL.

## Live Site

You can visit the live deployed site for the College Placement Backend at [https://nitjsr-backend.onrender.com](https://nitjsr-backend.onrender.com).

###License
This project is licensed under the MIT License.


In the `.env` file, replace `YOUR_MONGODB_URI` with the actual MongoDB connection URI obtained from MongoDB Atlas. This will ensure that your application connects to the appropriate MongoDB database.
