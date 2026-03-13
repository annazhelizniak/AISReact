
# Store Inventory and Financial Management System

Full-stack web application for managing store inventory, sales transactions, and financial records in a mini-supermarket.

The system provides tools for tracking products, managing inventory, processing sales, and monitoring financial activity through a REST API and a web interface.

---

# Tech Stack

**Frontend**
- React

**Backend**
- Node.js
- Express.js
- REST API

**Database**
- SQLite 

---

# Key Features

• Inventory management for store products  
• Sales transaction tracking with receipt generation  
• Financial records monitoring  
• Customer loyalty card support with discounts  
• Role-based access for **managers** and **cashiers**  
• Product search, filtering, and category management  
• Sales analytics and reporting  

---

# System Overview

The system supports two types of users:

### Manager
Managers control store operations and can:

- Manage products, categories, and inventory
- Manage employees and customer cards
- View sales history and financial reports
- Analyze product sales over selected time periods

### Cashier
Cashiers focus on sales operations and can:

- Process product sales and generate receipts
- Search products and customer cards
- View personal sales history
- Register new customers

---

# Database Design

The relational database schema includes the following main entities:

- **Product**
- **Store Product**
- **Category**
- **Employee**
- **Customer Card**
- **Receipt**
- **Sale**

The schema supports:

- product categorization
- inventory quantity tracking
- receipt generation with purchased items
- customer discount cards
- employee role management

The ER model and relational schema are defined in the project documentation.

---

# API

The backend exposes approximately **25 REST API endpoints** for:

- product management
- inventory updates
- receipt creation
- sales tracking
- customer card management
- employee management

These endpoints enable communication between the React frontend and the SQLite database.

---

# Example Functionalities

- Add, update, and delete products
- Track product quantities in the store
- Register new employees and customers
- Create receipts with multiple purchased products
- Calculate total price and VAT automatically
- Generate reports on product sales

The system keeps sales records for analysis and reporting.

---





## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
