# Encryption - A Web Application for Anonymous Secret Sharing

## Overview

Encryption is a web application where users can register, login, and share their secrets anonymously. Users can also sign in using Google OAuth. The application is built using Node.js, Express.js, and MongoDB. EJS is used as the templating engine to render the views.

## Table of Contents

- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contribution](#contribution)

## Installation and Setup

1. Clone the repository
    ```sh
    git clone https://github.com/Ashish-Chokhani/Encryption.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Encryption
    ```

2. Install dependencies
    ```sh
    npm install
    ```

3. Create a `.env` file in the root directory and add your Google OAuth credentials:
    ```plaintext
    CLIENT_ID=your_google_client_id
    CLIENT_SECRET=your_google_client_secret
    ```

4. Start the application
    ```sh
    node app.js
    ```

5. Open your browser and go to `http://localhost:3000`

## Usage

- **Home Page:** Displays the main page with options to register or login.
- **Register Page:** Allows new users to register with an email and password.
- **Login Page:** Allows existing users to login with an email and password or sign in using Google.
- **Secrets Page:** Displays all the shared secrets.
- **Submit Page:** Allows authenticated users to submit their secrets.

## Directory Structure

```bash
Encryption
│
├── public
│   ├── css
│   │   ├── styles.css
│   │   └── bootstrap-social.css
│
├── views
│   ├── partials
│   │   ├── header.ejs
│   │   └── footer.ejs
│   ├── home.ejs
│   ├── login.ejs
│   ├── register.ejs
│   ├── secrets.ejs
│   └── submit.ejs
│
├── .gitignore
├── app.js
├── package-lock.json
└── package.json
```

## Contribution
If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.
