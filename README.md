# React Project

This folder includes the UI implementation for PetPal web application. We have used React to develop an interaction and elegant User Unterface. Below are the pre-requsites and steps to setup the client application in your local machine.

## Prerequisites

Ensure you have the following software installed on your machine:

- Node.js (version 20 or above)
- npm (Node Package Manager) or yarn

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/infomediadesign/sad-01-24-petpal.git
    cd sad-01-24-petpal/client
    ```

2. **Install dependencies:**

    If you're using npm:

    ```bash
    npm install
    ```

3. **Start the development server:**

    If you're using npm:

    ```bash
    npm run dev
    ```

    This will start the development server and open the application in your default web browser. The app will be available at `http://localhost:5173`.






# PetPal Backend

This is the backend part of the PetPal project. This document will guide you through the structure of the backend and provide instructions on how to install and run the project.

## Folder Structure

The backend of PetPal is organized to ensure modularity and clarity.

- The **config** directory contains configuration files like `database.js` for database setup and `helper.js` for helper functions.
- The **controllers** directory houses business logic for different functionalities, such as `adoptionController.js` for pet adoptions and `authController.js` for authentication.
- The **models** directory defines data schemas, including `petsModel.js` and `careTakersModel.js`.
- The **routes** directory maps endpoints to controllers, with files like `petRoutes.js` and `authRoutes.js`.
- Utility functions are located in the **utils** folder, such as `imageUtil.js` for image processing. Finally, `server.js` is the main entry point that initializes the server and middleware.

- **server.js**: The main entry point of the application. Initializes the server and sets up middleware.

## Installation

### Steps

1. Navigate to server folder in the cloned respository:

```sh
cd server
```

2. Install dependencies:

```sh
npm install
```

3. Set up the database:
   Ensure your database is running and properly configured. Update the `config/database.js` file with your database credentials.

4. Start the server:

```sh
npm start
```
