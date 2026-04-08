# Installation Guide for Bandara Procurement System

## Prerequisites
Before you begin, ensure you have met the following requirements:

- **Node.js**: Download and install Node.js from [nodejs.org](https://nodejs.org/).
- **Git**: Install Git from [git-scm.com](https://git-scm.com/).
- **Database**: Set up a MongoDB database. You can use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for a cloud solution or install MongoDB locally.

## Setup Guide
1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourUsername/bandara-procurement-system.git
   cd bandara-procurement-system
   ```

2. **Install dependencies**:
   Navigate to the project directory and run:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**:
   - Create a new file named `.env` in the root directory of the project.
   - Add the following environment variables:
     ```ini
     MONGODB_URI=your_mongodb_connection_string
     PORT=3000
     SECRET_KEY=your_secret_key
     ```

4. **Run the application**:
   Start the server using the following command:
   ```bash
   npm start
   ```
   The application will be running on `http://localhost:3000`.

5. **Access the application**:
   Open your web browser and go to `http://localhost:3000` to access the Bandara Procurement System.

## Troubleshooting
- If you encounter issues, check the terminal for any error messages and ensure that all services are running as expected.
- Ensure that your MongoDB connection string is correct and that the database is accessible.

For further assistance, consult the project's documentation or contact the support team.