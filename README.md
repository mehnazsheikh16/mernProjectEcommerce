# MERN E-Commerce Project

A full-stack e-commerce application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This project is designed to teach and demonstrate how a real-world e-commerce application works, including authentication, product management, cart functionality, checkout flow, and admin features.


## Tech Stack

- Frontend: React.js, Redux, Material UI
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)
- Payments: Stripe
- File Storage: Cloudinary
- Email: Nodemailer

## Features

- User registration and login
- Product listing and product details
- Add to cart and update cart quantity
- Wishlist / favorites support
- Secure checkout using Stripe
- Order placement and order tracking
- Admin dashboard for product and order management
- JWT-based authentication
- Password hashing with bcrypt
- MongoDB database integration
- Responsive UI for desktop and mobile

## Project Structure

```bash
mernProjectEcommerce/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── app.js
│   ├── server.js
│   └── ...
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
├── .gitIgnore
├── Procfile
├── package.json
├── package-lock.json
├── README.md
└── ...
