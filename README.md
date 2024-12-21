# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
# Shopping Cart

This is a shopping cart application built with React and Vite. It allows users to browse products, add them to the cart, and manage the cart items.

## Features

- Browse a variety of products including hoodies, jackets, and shoes.
- Add products to the shopping cart.
- Update the quantity of items in the cart.
- Remove items from the cart.
- View the total price of items in the cart.
- Persistent cart data using local storage.

## Project Structure
shopping-cart/ ├── .gitignore ├── eslint.config.js ├── index.html ├── package.json ├── postcss.config.js ├── public/ │ └── images/ ├── README.md ├── src/ │ ├── App.jsx │ ├── assets/ │ │ └── data/ │ │ └── index.js │ ├── components/ │ │ ├── CartButtons.jsx │ │ ├── CartItem.jsx │ │ └── ShoppingCart.jsx │ ├── context/ │ │ └── cartContext.jsx │ ├── index.css │ ├── main.jsx │ └── utilities/ │ ├── formatCurrency.jsx │ └── localStorageFns.jsx ├── tailwind.config.js └── vite.config.js


## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/shopping-cart.git
   cd shopping-cart
   npm install

   Build
To build the project for production:
npm run build

Preview
To preview the production build:
npm run preview

Lint
To lint the codebase:

Configuration
ESLint
The project uses ESLint for code linting. Configuration can be found in eslint.config.js.

Tailwind CSS
Tailwind CSS is used for styling. Configuration can be found in tailwind.config.js and postcss.config.js.

License
This project is licensed under the MIT License.
