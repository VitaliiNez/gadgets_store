# Project Description: Gadgets Store

## Overview

The Gadgets Store project is a web-based application designed for buying accessories, phones, and tablets. Users can browse products, add them to favorites, manage a shopping cart, and make purchases. The application includes features for persisting user favorites and cart items using **redux-persist** to store data in **localStorage**. Built with React and TypeScript, the project utilizes modular SCSS for styling and integrates various libraries for enhanced functionality and user experience.

## Technologies Used

The Gadgets Store utilizes modern web technologies to provide a seamless shopping experience. Key technologies and libraries incorporated into the project include:

- **React:** Used for building the user interface with components managing different aspects of the store.
- **TypeScript:** Provides static type checking to improve code quality and development efficiency.
- **Redux Toolkit:** Used for state management, including **redux-persist** for persisting favorites and cart items in **localStorage**.
- **SCSS:** Modular SCSS stylesheets used for styling to create visually appealing interfaces.
- **React Router DOM:** Enables navigation within the application for seamless user experience and integrates with **searchParams** for managing URL query parameters.
- **Redux Toolkit Query (rtk-query):** Used for API data fetching and caching, enhancing performance and data management.
- **Other Libraries:** **classnames** for conditional CSS classes, **lodash.debounce** for debouncing input changes, **react-content-loader** for skeleton loading, and **swiper** for carousel functionality.

## Checkout Page

Currently, the checkout page is not implemented. Upon attempting to access the checkout page, users will be redirected to the main page of the Gadgets Store. Future updates will include a fully functional checkout process.

## Running the Project Locally

To run the Gadgets Store project locally, follow these steps:

1. **Clone the Repository:**
   `git clone https://github.com/VitaliiNez/gadgets_store.git`
2. **Navigate into the Project Directory:**
   `cd gadgets_store`
3. **Ensure Node.js Version:**
   The project requires Node.js version 14.21.3 to run. You can check your Node.js version with:
   `node -v`
   If necessary, use a version manager like [nvm](https://github.com/nvm-sh/nvm/) to install and switch to the correct version.
4. **Install Dependencies:**
   `npm install`
5. **Run the Project:**
   `npm start`

You can now explore the Gadgets Store locally in your web browser.

To access the live site, visit [Gadgets Store](https://VitaliiNez.github.io/gadgets_store/).
