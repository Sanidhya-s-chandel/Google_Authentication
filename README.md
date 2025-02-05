# Google Authentication

This repository contains an implementation of Google Authentication using OAuth 2.0. The project demonstrates how to integrate Google Sign-In into a web application for secure user authentication.

## Features
- Google OAuth 2.0 authentication
- Secure user login and logout
- User profile retrieval (name, email, profile picture)
- Session management

## Prerequisites
Before running the project, ensure you have the following:
- Node.js installed on your system
- A Google Developer Console account
- A registered OAuth 2.0 client ID and secret

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Sanidhya-s-chandel/Google_Authentication.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Google_Authentication
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Create a `.env` file in the root directory and add the following:
   ```sh
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   SESSION_SECRET=your_session_secret
   ```

## Usage
1. Start the server:
   ```sh
   npm start
   ```
2. Open your browser and go to:
   ```sh
   http://localhost:3000
   ```
3. Click on the "Sign in with Google" button to authenticate.

## Technologies Used
- Node.js
- Express.js
- Passport.js
- Google OAuth 2.0
- EJS (for rendering views)
- MongoDB (if applicable for storing user data)

## Contributing
Feel free to fork this repository and submit pull requests for improvements or additional features.

## License
This project is licensed under the MIT License.

## Contact
For any queries or issues, please contact [Sanidhya S Chandel](https://github.com/Sanidhya-s-chandel).

