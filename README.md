# MERN eCommerce Website with Stripe API Integration

Welcome to the MERN eCommerce website with Stripe API integration! This project is a full-stack web application that allows users to browse, search, and purchase products. It includes both the front-end (React) and back-end (Node.js/Express) components, as well as secure payment processing through the Stripe API.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Folder Structure](#folder-structure)
5. [Configuration](#configuration)
6. [Stripe Integration](#stripe-integration)
7. [License](#license)

## Prerequisites
Before you get started, make sure you have the following software and accounts set up:

- Node.js and npm installed.
- MongoDB database set up.
- Stripe account and API keys.

## Installation
1. Clone the repository:

   ```shell
   git clone https://github.com/Guadeloupe33/Full-Stack-Ecommerce-Website.git
   cd mern-ecommerce-stripe
Install server dependencies:

shell
Copy code
cd server
npm install
Install client dependencies:

shell
Copy code
cd ../client
npm install
Usage
Start the server:

shell
Copy code
cd ../server
npm start
Start the client:

shell
Copy code
cd ../client
npm start
Visit http://localhost:3001 in your web browser to access the eCommerce website.

Folder Structure
server: Contains the Node.js/Express server.
client: Contains the React front-end.
config: Configuration files for the server and Stripe keys.
models: MongoDB data models.
routes: API routes.
components: React components for the client.