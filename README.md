# 🛍️ E-Commerce Website

A responsive and interactive **E-Commerce Website** built using **HTML5, CSS3, Bootstrap 5, and JavaScript**. The project provides a basic online shopping experience where users can explore product categories, view products, add products to a shopping cart, manage cart items, simulate checkout, and view their order history.

The project uses **JavaScript and browser localStorage** to maintain cart and order data without requiring a backend server or database.

## 🚀 Features

### 🏠 Home Section

* E-Commerce website header
* Website logo/name
* Navigation menu
* Promotional banner
* Hero section
* Welcome message
* "Shop Now" button
* Responsive layout

### 🧭 Navigation Bar

The navigation bar provides access to:

* Home
* FAQ
* Your Orders
* My Cart
* Logout

The navigation bar is responsive and adapts to different screen sizes using Bootstrap.

### 🛍️ Product Categories

The website provides different shopping categories:

* Men's Wear
* Women's Wear
* Kids Wear

Each category contains an image, category name, and short description.

### ⭐ Featured Products

The website displays multiple featured products with:

* Product image
* Product name
* Product description
* Discount information
* Product price
* Add to Cart button

### 🛒 Shopping Cart

The shopping cart provides the following functionality:

* Add products to the cart
* Display the number of cart items
* Prevent duplicate products from being added
* Increase product quantity
* Decrease product quantity
* Remove products
* Clear the entire cart
* Display product details
* Calculate total price
* Save cart data in localStorage

### 💳 Checkout

The checkout functionality provides a frontend simulation of placing an order.

Users can:

* Review cart items
* View the total amount
* Proceed with checkout
* Place an order
* Clear the cart after placing an order

> This is a checkout simulation and does not process real payments.

### 📦 Order History

The Orders section allows users to view previously placed orders.

Order information is stored using browser `localStorage`, allowing the order history to remain available after refreshing the page.

### ❓ FAQ Section

The FAQ section provides commonly asked questions and answers related to the website and shopping process.

### 🚪 Logout

The Logout option provides a demo logout functionality for the frontend project.

> Since this project does not contain a backend authentication system, logout is simulated on the client side.

## 💾 Local Storage

The project uses the browser's **localStorage** to maintain data between page refreshes.

The following information can be stored:

* Cart items
* Product quantities
* Order history

Example:

```javascript
localStorage.setItem("cart", JSON.stringify(cart));
```

Cart information is retrieved when the website loads:

```javascript
let cart = JSON.parse(localStorage.getItem("cart")) || [];
```

This allows the shopping cart to persist in the browser.

## 📱 Responsive Design

The website is designed to work across different screen sizes:

* 💻 Desktop
* 📱 Mobile
* 📲 Tablet

Bootstrap's responsive grid system, utilities, and components are used to create the responsive layout.

## 🎨 User Interface

The website includes:

* Clean navigation bar
* Product cards
* Category cards
* Responsive grid layout
* Buttons and interactive elements
* Product images
* Promotional sections
* Shopping cart interface
* Order history interface
* Footer section

Custom CSS is used along with Bootstrap to improve the appearance of the website.

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript

### Browser Storage

* localStorage

### External Resources

* Bootstrap CDN
* Google Fonts
* External product/category images

## 📂 Project Structure

```text
E-Commerce-Website/
└── index.html
```

The project is implemented in a single `index.html` file containing:

* HTML structure
* CSS styling
* Bootstrap classes
* JavaScript functionality

## ⚙️ Main JavaScript Functionality

JavaScript is used to make the website interactive.

The main functionality includes:

* Selecting product elements
* Handling Add to Cart button clicks
* Creating product objects
* Managing the cart array
* Checking for duplicate products
* Updating cart quantities
* Removing cart items
* Calculating cart totals
* Saving cart data to localStorage
* Retrieving cart data from localStorage
* Creating and storing orders
* Updating the cart item count
* Managing checkout
* Handling demo logout

## 🔄 Application Flow

```text
Open Website
      ↓
Browse Categories
      ↓
View Featured Products
      ↓
Add Product to Cart
      ↓
Cart Data Saved in localStorage
      ↓
Open Cart
      ↓
Manage Quantity / Remove Items
      ↓
View Total Price
      ↓
Checkout
      ↓
Order Created
      ↓
Order Saved in localStorage
      ↓
Cart Cleared
      ↓
View Order History
```

## 🎯 Project Purpose

This project was created to practice and demonstrate:

* HTML5 page structure
* CSS styling
* Bootstrap framework
* Bootstrap responsive grid system
* Responsive web design
* Navigation bars
* Cards
* Buttons
* Product layouts
* JavaScript DOM manipulation
* JavaScript event handling
* Arrays and objects
* localStorage
* Cart management
* Basic checkout flow
* Order management
* Frontend E-Commerce concepts

## ▶️ How to Run

1. Download or clone this repository.

2. Open the project folder.

3. Open the `index.html` file.

4. The website will open in your default web browser.

5. Browse the products and test the shopping cart functionality.

No additional installation or server setup is required for the basic frontend version.

## 🌐 Browser Compatibility

The project can be opened in modern browsers such as:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

## ⚠️ Project Limitations

This is a **frontend-only E-Commerce project**.

It does not currently include:

* Real backend server
* Database
* Real user registration
* Real user authentication
* Real payment gateway
* Real payment processing
* Real product management system
* Real-time inventory management
* Production order processing

The cart and order functionality is implemented using JavaScript and browser `localStorage`.

## 🔮 Future Improvements

The project can be extended in the future with:

* User registration and login
* Backend API
* MongoDB database
* Product search
* Product filtering
* Product sorting
* Product details page
* Wishlist functionality
* Real shopping cart page
* Address management
* Real payment gateway
* Order tracking
* Admin dashboard
* Product management
* Inventory management
* User profile
* JWT authentication

These improvements can transform the frontend project into a complete **MERN Stack E-Commerce Application**.

## 📸 Project Highlights

The project demonstrates a basic shopping workflow:

**Browse → Select Product → Add to Cart → Manage Cart → Checkout → Place Order → View Orders**

## 👨‍💻 Author

**Tarak Sai**

B.Tech Information Technology Student

## 📄 License

This project is created for **educational and learning purposes**.
