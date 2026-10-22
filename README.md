# ecom — E-Commerce Web Application with Node.js, Express, EJS & MySQL

A full-featured **e-commerce web application** built with **Node.js and Express**, server-rendered with **EJS templates**, and backed by a **MySQL** database. It includes user authentication, session management, form validation, and image upload support — a practical foundation for online stores, shopping-cart websites, and Node.js e-commerce projects.

## Features

- Server-rendered storefront using **EJS templating** with Express
- **User authentication** with hashed passwords (bcrypt) and JWT support
- **Session management** via express-session for cart and login state
- **MySQL database** layer using the mysql2 driver
- **File/image uploads** with Multer (e.g. product images)
- **Input validation** with express-validator
- Environment-based configuration with dotenv
- Test tooling included (Jest, Mocha, Chai, Supertest) for API and route testing

## Tech Stack

- Node.js + Express 4
- EJS (Embedded JavaScript templates)
- MySQL (mysql / mysql2)
- bcrypt, jsonwebtoken, express-session
- Multer, express-validator, cors, body-parser, dotenv

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- MySQL server

### Installation

```bash
git clone https://github.com/sh00von/ecom.git
cd ecom
npm install
```

Create a `.env` file in the project root with your database and app configuration (host, user, password, database name, session/JWT secrets), create the MySQL database, then start the app:

```bash
node app.js
```

Then open the store in your browser at the configured port (see `app.js` / your `.env`).

## Usage

Browse the storefront, register or log in as a customer, add products to the cart, and check out — product images are handled through the built-in Multer upload pipeline, and all form submissions are validated server-side.

---

⭐ Building a Node.js online store? Star this repo if it helps, and feel free to open issues or contribute improvements!
