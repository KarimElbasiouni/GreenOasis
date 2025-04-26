# Green Oasis - Plant E-commerce Application

![Green Oasis](https://cdn.pixabay.com/photo/2021/01/22/06/04/snake-plant-5939187_1280.jpg)

## Overview

Green Oasis is a modern React-based e-commerce application focused on indoor plants. The application offers a curated selection of plants categorized by their uses and benefits, allowing users to explore and purchase plants that match their specific needs and preferences.

Green Oasis is the final project of the course Developing Front-End Apps with React created by IBM, which is available on Coursera through Coursera.

# Preview
- [Click here for a preview!](https://karimelbasiouni.github.io/GreenOasis/)

## Features

- **Landing Page**: Attractive welcome page with a "Get Started" button to navigate to the shop
- **About Us Section**: Information about the Green Oasis brand and mission
- **Product Catalog**: Organized plant categories including:
  - Air Purifying Plants
  - Aromatic Fragrant Plants
  - Insect Repellent Plants
  - Medicinal Plants
  - Low Maintenance Plants
- **Shopping Cart**: Fully functional cart with the following features:
  - Add/remove items
  - Adjust quantities
  - View item details
  - Calculate total cost
- **Responsive Design**: Works well on multiple device sizes

## Technical Stack

- **Frontend Framework**: React 18
- **State Management**: Redux (with Redux Toolkit)
- **Build Tool**: Vite
- **Styling**: CSS (component-based styling)
- **Deployment**: GitHub Pages

## Project Structure

```
src/
├── assets/           # Static assets like images
├── App.jsx           # Main application component
├── App.css           # Styles for App component
├── AboutUs.jsx       # About Us section component
├── AboutUs.css       # Styles for About Us component
├── ProductList.jsx   # Product catalog component
├── ProductList.css   # Styles for product listings
├── CartItem.jsx      # Shopping cart item component
├── CartItem.css      # Styles for cart items
├── CartSlice.jsx     # Redux slice for cart state management
├── store.js          # Redux store configuration
├── main.jsx          # Application entry point
└── index.css         # Global styles
```

## State Management

The application uses Redux for state management, specifically focusing on the shopping cart functionality:

- **Cart State**: Managed through `CartSlice.jsx`
- **Actions**:
  - `addItem`: Add product to cart
  - `removeItem`: Remove product from cart
  - `updateQuantity`: Update product quantity in cart

## User Flow

1. User lands on the welcome page with brand introduction
2. User clicks "Get Started" to view the plant catalog
3. User can browse plants by category
4. User can add plants to the shopping cart
5. User can view cart, update quantities, or remove items
6. User can continue shopping or proceed to checkout

## Product Data

The application features a diverse array of plants organized into categories:

- **Air Purifying Plants**: Snake Plant, Spider Plant, Peace Lily, etc.
- **Aromatic Fragrant Plants**: Lavender, Jasmine, Rosemary, etc.
- **Insect Repellent Plants**: Oregano, Marigold, Geraniums, etc.
- **Medicinal Plants**: Aloe Vera, Echinacea, Peppermint, etc.
- **Low Maintenance Plants**: ZZ Plant, Pothos, Snake Plant, etc.

Each plant includes:
- Name
- Image
- Description
- Price

## Running the Project Locally

```bash
# Clone the repository
git clone <repository-url>

# Navigate to project directory
cd green-oasis

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

The project is configured for deployment to GitHub Pages:

```bash
# Deploy to GitHub Pages
npm run deploy
```

## Future Enhancements

- User authentication system
- Checkout and payment processing
- User reviews and ratings
- Plant care instructions
- Search functionality
- Filtering options

## License

This project is licensed under the terms included in the LICENSE file.

---
