# PWA Text Editor (J.A.T.E - Just Another Text Editor)

This project is a **Progressive Web Application (PWA)** designed to function as an offline/online text editor. The application is developed to be installable on your local device and usable even without an internet connection, thanks to its PWA features.

## Features

- **Offline Functionality**: Works seamlessly without an internet connection using service workers and caching.
- **Installable**: Users can install the text editor directly onto their devices as a standalone application.
- **Modern Front-End**: Developed using the latest web technologies.
- **Simple and Efficient**: Provides a clean interface for text editing.

## Project Structure

The application is structured as a full-stack web application using **Express.js** for the backend and a client-side **React** app:

```plaintext
PWA-text-editor-pro-main/
├── client/               # Front-end of the application
│   ├── public/           # Static assets
│   ├── src/              # React components and client-side logic
│   └── package.json      # Client dependencies and scripts
├── server/               # Backend server
│   ├── server.js         # Express.js server setup
│   └── package.json      # Server dependencies and scripts
├── .gitignore            # Git ignore rules
├── .npmrc                # npm configuration
├── LICENSE               # License information
├── README.md             # This README file
├── package.json          # Main dependencies and project metadata
└── package-lock.json     # Lock file for npm dependencies

## Front-End

The client-side is built with **React** and includes PWA features like service workers and a manifest file to enable offline usage and installability.

## Back-End

The back-end uses **Express.js** to serve the application and manage routing for any server-side requirements.

## Installation

To set up the application locally, follow these steps:

### Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/PWA-text-editor-pro-main.git
cd PWA-text-editor-pro-main

## Installation

To set up the application locally, follow these steps:

### Install dependencies:

```bash
npm run install

This will install the dependencies for both the client and the server.

Run the application in development mode:
bash
Copy code
npm run start:dev
This will concurrently run both the server and the client for development purposes.

##To build the client for production:
bash
Copy code
npm run build
This will create a production build of the React client.

##To start the server in production:
bash
Copy code
npm run start

## Scripts

Here are the key npm scripts available:

- **start**: Runs both the client and server concurrently in development mode.
- **start:prod**: Builds the client and starts the server in production.
- **build**: Creates a production build of the client.
- **install**: Installs dependencies for both client and server.
- **client**: Starts the client in development mode.
- **server**: Starts the server using nodemon.

## PWA Features

This application is configured as a **Progressive Web App (PWA)**, allowing for:

- **Offline Functionality**: Users can continue editing even when offline.
- **Installability**: Users can install the application on their devices.
- **Caching**: Efficient use of service workers to cache assets for quick load times and offline access.

## Dependencies

- **Express.js**: Backend web framework for routing and serving the application.
- **Concurrently**: Used to run the client and server simultaneously during development.

## License

This project is licensed under the **ISC License**. See the [LICENSE](LICENSE) file for details.
