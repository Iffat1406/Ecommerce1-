# ShopVibe Shopping 
---

**Overview**
---

This is an eCommerce platform that allows users to browse products, place orders, and make payments online. The site offers features like product filtering, a shopping cart.
---

**Features**
---

-Product Catalog: Browse products by category
- User Accounts: Users can register, log in, and manage orders.
- Shopping Cart: Add products to the cart and modify quantities before checkout.
- Secure Checkout: Online Payment
- Order Tracking: Real-time order status updates.
- Reviews and Ratings: Customers can leave feedback and rate products.
- Responsive Design: Fully mobile-responsive for a seamless experience across devices.
---

**Technologies used**
---

- Frontend: HTML, CSS, JavaScript, React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)
- Payment Integration: PayPal 
- Other Libraries/Tools:
    - bcryptjs for password hashing
    - axios for API calls
    - React Router for navigation
    - Mongoose for MongoDB interaction
---
**Step to run**
---
1. Clone this repository
2. Install dependencies for both the backend and frontend:
     - Backend: ``cd server ``, ``npm install``
     - Frontend: ``cd client``, ``npm install``
3. Set up environment variables:
    - Create a .env file in the server directory and add your environment variables
4. Start the server and frontend:
    - Backend: ``cd server``, ``npm start``
    - Frontend: ``cd client``, ``npm start``
5. Open the app in your browser at http://localhost:5173.


**Usage**
---
1. Create an Account: Navigate to the registration page and sign up using an email and password.
2. Browse Products: Use the product catalog to filter and search for items.
3. Add to Cart: Select products and add them to your shopping cart.
4. Checkout: Proceed to the checkout page, where you can enter shipping details and make payments.
5. Track Orders: Once the order is placed, you can track it via your user dashboard.
---

**Folder Structure**
---
1. server/ – Backend code, including API routes, database   models, and authentication.
2. client/ – Frontend code built with React, including components, pages, and styling.
3. .env – Environment variables 
4. README.md – 