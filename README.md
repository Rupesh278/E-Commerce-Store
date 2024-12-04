An advanced e-commerce platform featuring MongoDB for database management, Redis for caching, and Stripe for payment processing. This project includes robust JWT-based authentication with bcrypt for password security, a full-featured admin dashboard, and a responsive UI built with Tailwind CSS. The platform supports core e-commerce functionalities such as product and category management, a secure shopping cart, and a streamlined checkout process.


**Features**

1. Authentication and Authorization
>  - JWT-based authentication system with refresh and access tokens for secure session management.
>  - Passwords hashed with bcrypt for enhanced security.
2. Product and Category Management
>  - Admin dashboard for adding, editing, and organizing products and categories.
>  - Coupon code creation and management for promotions and discounts.
3. Shopping Cart and Checkout
>  - User-friendly shopping cart that retains items across sessions.
>  - Integrated Stripe payment gateway for secure transactions.
4. Sales Analytics
>  - Real-time sales analytics with insights into product performance and revenue trends.
5. Responsive Design
>  - Tailwind CSS for a fully responsive and consistent UI across desktop and mobile devices.

**Tech Stack**

- Frontend: HTML, CSS, JavaScript, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Caching: Redis
- Authentication: JWT (JSON Web Token), bcrypt
- Payment Integration: Stripe

**Configuration**

- MongoDB: Used as the primary database to store products, users, and orders.
- Redis: Configured for session caching, improving performance.
- Stripe: Set up for secure payment processing.
- JWT & Bcrypt: Configured for user authentication and password security.

**Usage**

- Admin Dashboard: Accessible to administrators for managing products, categories, and viewing sales analytics.
- User Signup/Login: Users can create accounts, log in, and securely manage their sessions with JWT.
- Shopping & Checkout: Users can add items to the cart, apply coupon codes, and securely complete purchases using Stripe.
