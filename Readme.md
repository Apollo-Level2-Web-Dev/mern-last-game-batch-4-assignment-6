# MERN Last Game!

## Assignment Requirements: E-Commerce Web Application with Next.js

**Objective:**

Develop a full-stack e-commerce application using **Next.js** that allows both **Admin** and **User** roles to manage and interact with products, orders, payments effectively. The application should focus on providing a seamless user experience and intuitive admin functionalities.

---

### 1. **User Roles and Permissions**

### **Admin Role:**

-  **User Management:**
   -  **Create User:** Admin can create new user accounts with roles (Admin/User).
   -  **View Users:** Admin can view a list of all registered users with details.
   -  **Edit User:** Admin can modify user information, such as changing roles.
   -  **Delete User:** Admin can delete user accounts as needed.
-  **Product Management:**
   -  **Add Product:** Admin can add new products to the inventory, providing details such as:
      -  Product Name
      -  Description
      -  Price
      -  Stock Quantity
      -  Category
      -  Product Images
   -  **Edit Product:** Admin can update existing product details.
   -  **Delete Product:** Admin can remove products from the inventory.
   -  **View Products:** Admin can see a list of all products with options to filter and search.
-  **Product Categories Management:**
   -  **Add Category:** Admin can create new product categories to organize products.
   -  **Edit Category:** Admin can modify existing categories.
   -  **Delete Category:** Admin can remove categories.
-  **Order & Payment Management:**
   -  **View Orders:** Admin can view all orders placed by users, along with status and details.
   -  **Cancel Orders:** Admin can cancel orders as required.

### **User Role:**

-  **Product Browsing:**
   -  **Search Products:** Users can search for products using keywords.
   -  **Filter Products:** Users can filter products by categories, price range, and other attributes.
   -  **Pagination:** Users can navigate through product listings with pagination.
-  **Product Details:**
   -  **View Product:** Users can view detailed information about products, including descriptions, prices, and reviews.
   -  **Browse by Category:** Users can browse products by selecting categories.
-  **Cart Functionality:**
   -  **Add to Cart:** Users can add products to their shopping cart.
   -  **View Cart:** Users can view all products in their cart with the ability to modify quantities or remove items.
   -  **Checkout:** Users can proceed to a checkout page to confirm their order.
-  **Order and Payment:**
   -  **Make Online Payments:** Users can pay for their orders using integrated payment gateways.
   -  **View Order History:** Users can view a history of their past orders with details.

---

### 2. **Features Breakdown**

### Admin Features:

1. **User Management:**
   -  **User List Page:** Display all users with options to create, edit, or delete users.
   -  **User Detail Page:** View and modify user details.
2. **Product Management:**
   -  **Product List Page:** Display all products with search and filter functionalities.
   -  **Add/Edit Product Form:** Form to input product details, including images (using a file upload mechanism).
   -  **Product Detail View:** Admin can view detailed product information.
3. **Product Categories Management:**
   -  **Category Management Page:** Add, edit, or delete product categories.
4. **Order Management:**
   -  **Order List Page:** Display all orders with status updates and actions to modify orders.
   -  **Order Detail View:** View specific order details and history.
5. **Payment Management:**
   -  **Payment Records Page:** View a list of payments made by users, with details on payment status.

### User Features:

1. **Home Page:**
   -  **Product Display:** Show all products with options for search, filtering by category, and pagination.
   -  **Branding or Hero Section**
   -  **Featured Products:** Highlight new or popular products.
   -  **Footer**
2. **Product Details Page:**
   -  **Product Information:** Display all relevant product details, including images and reviews.
   -  **Add to Cart Button:** Allow users to add the product to their cart directly.
3. **Cart Page:**
   -  **Cart Summary:** List all items in the cart, displaying subtotal and total prices.
   -  **Modification Options:** Allow users to change quantities or remove items.
4. **Checkout Page:**
   -  **Checkout Form:** Collect shipping and billing information.
   -  **Payment Integration:** Implement an online payment gateway for processing payments (Aamarpay).
5. **Order History Page:**
   -  **Order List:** Display past orders with details such as date, products, total amount, and status.

---

### 3. **Pages to Implement**

### **1. Home Page (`/`):**

-  **Layout:**
   -  Header with navigation links (Home, Products, Cart, etc.)
   -  Main section displaying products with search, filtering, and pagination.
   -  Footer with links to contact, terms, and privacy policy.

### **2. Product Details Page (`/product/[id]`):**

-  **Layout:**
   -  Product images and description.
   -  Price and stock information.
   -  Add to Cart button.
   -  Reviews section with a form to submit a new review.

### **3. Cart Page (`/cart`):**

-  **Layout:**
   -  List of items in the cart with quantity adjustment options.
   -  Total price summary and checkout button.

### **4. Checkout Page (`/checkout`):**

-  **Layout:**
   -  Form for shipping and billing details.
   -  Summary of items in the cart and total price.
   -  Payment processing button.

### **5. Order History Page (`/orders`):**

-  **Layout:**
   -  List of previous orders with details and statuses.

### **6. Admin Dashboard:**

-  **User Management Page:**
   -  List of users with options to add, edit, or delete.
-  **Product Management Page:**
   -  List of products with add/edit/delete functionality.
-  **Order Management Page:**
   -  List of orders with status updates.

---

### 4. **Technical Requirements**

-  **Frontend:**
   -  Use **Next.js** (React framework) to create a server-rendered application.
   -  Implement **TypeScript** for type safety.
-  **Backend:**
   -  Set up a separate **Node.js** and **Express.js** server with Typescript.
   -  Use **TypeScript** for server-side code.
   -  Integrate with **MongoDB** with **Mongoose** for database interactions.
-  **Authentication & Authorization:**
   -  Use **JWT (JSON Web Tokens)** for secure user authentication.
   -  Implement role-based access control to restrict admin functionalities.
-  **Payment Integration:**
   -  Choose a payment gateway (e.g., **Stripe**, **AmarPay**) and integrate it into the checkout process.
-  **Deployment:**
   -  Deploy the application on a cloud platform such as **Vercel** (recommended for Next.js)

---

### 5. **Bonus Points**

-  **Server-Side Rendering (SSR):** Implement SSR or Static Site Generation (SSG) for optimal performance and SEO.
-  Mobile-friendly design is essential, with responsive layouts that work seamlessly on any device.
-  Implement smooth transitions, hover effects, and subtle animations to improve the user experience, making the platform feel responsive and engaging.

---

### Submission Requirements:

-  **GitHub Repository:** Provide a link to the GitHub repository containing the source code.
-  **Live Deployment:** Provide a link to the live application.
-  **Demo Video:** Create a project demo video (max 5 minutes) showcasing all features and functionalities of the application.
  

### ⏰ **Submission Deadline:**

- 30 Marks: November 03, 2024, 11.59 PM ⏳

