# Amazon Clone

A fully responsive e-commerce web application built with HTML, CSS, and JavaScript that replicates core Amazon shopping functionality.

## Features

- **Product Catalog**: Browse a dynamic product listing with images, ratings, and prices
- **Shopping Cart**: Add/remove items and manage quantities with real-time cart updates
- **Checkout**: Complete checkout experience with order summary
- **Order Management**: View order history and track orders
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop screens
- **Search Functionality**: Find products efficiently
- **Product Ratings**: View customer ratings and reviews for each product

## Project Structure

```
AmazonClone/
├── index.html              # Main product listing page
├── checkout.html           # Checkout page
├── orders.html             # Order history page
├── tracking.html           # Order tracking page
├── css/
│   ├── shared/             # Shared styles
│   │   ├── general.css     # General styling
│   │   └── header.css      # Header styling
│   └── pages/              # Page-specific styles
│       ├── index.css
│       ├── orders.css
│       ├── tracking.css
│       └── checkout/
│           ├── checkout-header.css
│           └── checkout.css
├── js/
│   └── index.js            # Main JavaScript functionality
├── data/
│   ├── cart.js             # Shopping cart logic
│   └── products.js         # Product data
├── backend/
│   └── products.json       # Product database
└── images/                 # Images and icons
    ├── products/
    ├── icons/
    └── ratings/
```

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Responsive design and styling (flexbox/grid)
- **JavaScript (ES6+)**: DOM manipulation and interactivity
- **Responsive Web Design**: Mobile-first approach

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server installation required


## Usage

1. **Browse Products**: Start on the home page to see available products
2. **Add to Cart**: Select quantity and click "Add to Cart" for any product
3. **View Cart**: Click the cart icon to review your items
4. **Checkout**: Proceed to checkout and review your order
5. **View Orders**: Navigate to the Orders page to see your purchase history
6. **Track Orders**: Use the tracking page to monitor order status

## Features in Detail

### Product Display
- Dynamic product rendering from JavaScript data
- Product images, names, prices, and ratings
- Quantity selector (1-10 items)

### Shopping Cart
- Persistent cart state during session
- Real-time cart quantity updates in header
- Add/remove functionality

### Responsive Design
- Mobile-optimized layout
- Tablet adaptations
- Desktop full-width experience

## Future Enhancements

- [ ] Backend API integration
- [ ] User authentication and accounts
- [ ] Payment gateway integration
- [ ] Database for persistent storage
- [ ] Product filtering and sorting
- [ ] Advanced search capabilities
- [ ] Customer reviews and ratings submission
- [ ] Wishlist functionality
- [ ] Order status notifications

## File Guide

| File | Purpose |
|------|---------|
| `index.html` | Homepage with product listing |
| `checkout.html` | Shopping cart and checkout interface |
| `orders.html` | User's order history |
| `tracking.html` | Order tracking details |
| `data/products.js` | Product database (JavaScript objects) |
| `data/cart.js` | Shopping cart management logic |
| `js/index.js` | Main application JavaScript |

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


---

**Note**: This is a frontend-only clone for educational purposes. For production use, integrate with a proper backend and payment processing service.
