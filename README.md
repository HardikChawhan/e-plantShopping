# Paradise Nursery - E-Plant Shopping Application

A modern, responsive React-based e-commerce application for purchasing houseplants. Built with Redux for state management and featuring a clean, intuitive user interface.

## Features

### Landing Page
- Attractive background image with company branding
- Company information and mission statement
- "Get Started" button to navigate to the product catalog

### Product Listing Page
- 30+ unique houseplants organized into 5 categories:
  - Air Purifying Plants
  - Aromatic Fragrant Plants
  - Insect Repellent Plants
  - Medicinal Plants
  - Low Maintenance Plants
- Each plant displays:
  - High-quality thumbnail image
  - Plant name and description
  - Price
  - Add to Cart functionality
- Dynamic cart icon showing total item count
- Responsive grid layout

### Shopping Cart Page
- Complete cart management:
  - View all added items
  - Increase/decrease quantities
  - Remove items completely
  - Real-time total calculation
- Cart displays:
  - Individual item details (image, name, price)
  - Quantity controls
  - Subtotal per item type
  - Grand total for all items
- Continue Shopping and Checkout buttons

### Navigation & UX
- Seamless navigation between all pages
- Header with shopping cart icon and count
- Responsive design for all screen sizes
- Smooth animations and transitions

## Technologies Used

- **React 18** - Frontend framework
- **Redux Toolkit** - State management
- **Vite** - Build tool and development server
- **CSS3** - Styling with modern features
- **JavaScript ES6+** - Modern JavaScript features

## Installation & Setup

1. Clone the repository:
```bash
git clone [your-repo-url]
cd e-plantShopping
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173/shoppingreact`

## Project Structure

```
src/
├── App.jsx          # Main application component
├── App.css          # Landing page styles
├── ProductList.jsx  # Product catalog component
├── ProductList.css  # Product listing styles
├── CartItem.jsx     # Shopping cart component
├── CartItem.css     # Cart styling
├── CartSlice.jsx    # Redux cart state management
├── AboutUs.jsx      # Company information component
├── AboutUs.css      # About us styles
├── store.js         # Redux store configuration
├── main.jsx         # Application entry point
└── index.css        # Global styles
```

## Redux State Management

The application uses Redux Toolkit for efficient state management:

- **Cart State**: Manages items, quantities, and cart operations
- **Actions**: 
  - `addItem` - Add products to cart
  - `removeItem` - Remove products from cart
  - `updateQuantity` - Modify item quantities

## Responsive Design

The application is fully responsive and works seamlessly across:
- Desktop computers
- Tablets
- Mobile phones

## Build & Deployment

To build for production:
```bash
npm run build
```

To preview the production build:
```bash
npm run preview
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License.

## Author

Created as part of a React final project demonstrating modern web development practices and e-commerce functionality.