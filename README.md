# Yugen Nextgen Ecommerce Store Application 🛒

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Key Features](#features)
  - [File Structure](#file-structure)
  - [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Future Improvements](#future-improvements)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The **Yugen Nextgen E-Commerce Store Application** is a modern full-stack e-commerce platform built using **Next.js**. The app allows users to browse products, add them to their cart, and proceed to checkout using **Stripe** for payments. Additionally, it features an **Admin Dashboard** and **Content Management System (CMS)** for managing products, orders, and user data. The project aims to provide a scalable and responsive e-commerce solution with a smooth user experience.

### The challenge
The goal of this project was to build a fully functional e-commerce platform with the following requirements:
- **Frontend:** Users can browse and search products, add items to the cart, and complete the checkout process.
- **Admin Dashboard:** A dashboard to manage product listings, view orders, and update product details.
- **Payment Integration:** Secure payment gateway integration via **Stripe** for handling transactions.
- **Content Management System:** Easy-to-use CMS for managing products and orders.
- **Full-stack Architecture:** Using Next.js for both the client-side and server-side logic, ensuring a smooth experience and SEO optimization.

### Features
- **Product Catalog:** Displays products with images, descriptions, and prices.
- **Shopping Cart:** Users can add/remove items, view totals, and proceed to checkout.
- **Stripe Integration:** Secure payment gateway for handling payments.
- **Admin Dashboard:** For managing product inventory, orders, and viewing customer details.
- **CMS Functionality:** Admins can add, edit, and delete products directly from the dashboard.
- **Responsive Design:** Built with mobile-first principles for a smooth experience on all devices.
- **User Authentication:** Secure login and registration for users and admins.

### File Structure
```
/root-directory
|-- .github/workflows/           # GitHub workflows for CI/CD
|-- .gitignore                   # Files to be ignored by Git
|-- LICENSE                      # Project license
|-- README.md                    # Project description and instructions
|-- components/                  # React components for UI
|-- pages/                       # Next.js pages for frontend and admin
|-- server/                      # Server-side logic (API routes)
|-- public/                      # Static files (images, fonts)
|-- styles/                      # CSS or styled-components
|-- stripe/                      # Stripe-related logic for payments
|-- package.json                 # Project dependencies and scripts
```

### Technologies Used
- **Next.js** for server-side rendering, routing, and API routes
- **Stripe** for secure payment processing
- **React** for building the user interface
- **MongoDB** for storing product, order, and user data
- **Node.js** for backend API and server-side logic
- **Tailwind CSS** for responsive styling
- **JWT** for user authentication and session management

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- npm (or Yarn)
- Stripe account for payment integration
- MongoDB instance (local or cloud-based)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yugen-nextgen_ecommerce_store_application.git
   ```
2. Navigate to the project directory:
   ```bash
   cd yugen-nextgen_ecommerce_store_application
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Create a `.env.local` file in the root directory and add your environment variables (e.g., Stripe API keys, MongoDB URI, etc.):
   ```
   NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
   STRIPE_SECRET_KEY=your_stripe_secret_key
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
5. Run the development server:
   ```bash
   npm run dev
   ```

### Usage
1. **Frontend Usage:** Users can browse products, add them to the cart, and complete their purchase using the Stripe payment gateway.
2. **Admin Dashboard:** Admins can manage the products and orders, including adding new products, editing existing ones, and viewing order details.
3. **Payment Integration:** When checking out, users will securely pay via Stripe. The payment process is handled on the backend.

### Future Improvements
- Add support for multiple payment methods (e.g., PayPal).
- Implement **order status tracking** (e.g., Pending, Shipped, Delivered).
- Build a **review system** where users can leave reviews for purchased products.
- Add **inventory management** and automated stock updates in the Admin Dashboard.

### Useful resources

- [Next.js Documentation](https://nextjs.org/docs) - Official Next.js documentation for server-side rendering and routing.
- [Stripe API Documentation](https://stripe.com/docs) - Official guide for integrating Stripe payments into your app.
- [MongoDB Documentation](https://docs.mongodb.com/) - Guide for using MongoDB with your application.
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - Tailwind CSS documentation for utility-first CSS styling.
- [JWT Authentication Tutorial](https://jwt.io/introduction/) - Guide to using JWT for secure authentication.

## Author

<b><strong>Sarthak Sachdev</strong></b>
- Website - [Sarthak Sachdev](https://itsmesarthak.netlify.app/)
- LinkedIn - [Sarthak Sachdev](https://www.linkedin.com/in/sarthak2004/)
- Twitter - [@sarthak_sach69](https://www.twitter.com/sarthak_sach69)

## Acknowledgments

A huge thanks to the teams behind **Next.js**, **Stripe**, and **MongoDB** for their amazing documentation and tools. Additionally, I appreciate the contributions of the open-source community that made building this project easier and faster.

## Got feedback for me?

Feel free to send me an email at saarsaach30[at]gmail[dot]com with any feedback or suggestions!

## Contributing
Contributions are welcome! Fork the repository, make changes, and submit a pull request.

## License📃
This project is licensed under the MIT License.

Copyright (c) 2024, Sarthak Sachdev

**Happy coding!** 😊🚀
