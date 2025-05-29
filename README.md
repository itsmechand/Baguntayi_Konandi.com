# Product List Application

A dynamic web application that displays and filters products from various categories.

## Features

- Display all products
- Filter products by category:
  - Electronics
  - Men's Clothing
  - Women's Clothing
  - Jewelry
- Product cards show:
  - Product ID
  - Title
  - Price
  - Image
  - Rating (with stars and review count)

## Project Structure

```
├── index.html          # Main HTML file
├── script.js          # JavaScript file containing product data and functions
└── README.md          # This documentation file
```

## Setup Instructions

1. Clone the repository
2. Open `index.html` in your web browser
3. No additional setup required - the application runs directly in the browser

## Usage

- Click "All Products" to view all available products
- Use category buttons to filter products:
  - "Electronics" for electronic items
  - "Men's" for men's clothing
  - "Women's" for women's clothing
  - "Jewelry" for jewelry items

## Code Structure

### Main Functions

- `handleAllProducts()`: Displays all products
- `handleElectronics()`: Filters and displays electronics
- `handlemen()`: Filters and displays men's clothing
- `handlewomen()`: Filters and displays women's clothing
- `show_products_to_user()`: Renders products in the UI

### Data Structure

Products are stored in the `products_data` array with the following properties:
- id: Unique identifier
- title: Product name
- price: Product price
- category: Product category
- image: URL to product image
- rating: Object containing rate and count

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)

## Browser Support

The application works in all modern browsers that support ES6+ JavaScript features. 