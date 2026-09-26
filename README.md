# Avinyaa Food Processing - Backend API

This is the Node.js/Express backend for the Avinyaa Food Processing website. It handles contact form submissions and sends automated emails using Nodemailer.

## How to Run Locally

1. Install dependencies:
   npm install

2. Create a `.env` file in the root directory and add your credentials:
   PORT=5000
   EMAIL_USER=your-email@gmail.com
   EMAIL_PASS=your-16-digit-app-password
   RECEIVER_EMAIL=your-email@gmail.com

3. Start the server:
   node server.js

## Tech Stack
* Node.js
* Express
* Nodemailer
* CORS
* Dotenv
