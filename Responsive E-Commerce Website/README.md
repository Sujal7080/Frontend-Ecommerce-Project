# SHOP.CO - Responsive E-Commerce Website

A modern, fully responsive e-commerce website built with HTML and CSS, featuring a clean design and smooth user experience across all devices.

## 🌟 Features

- **Fully Responsive Design** - Seamlessly adapts to desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean and intuitive interface with smooth animations
- **Mobile-First Navigation** - Hamburger menu with slide-in animation for mobile/tablet
- **Product Filtering** - Advanced filter system with slide-in panel on mobile
- **Interactive Elements** - Color selectors, size options, quantity controls
- **Product Reviews** - Customer feedback section with ratings
- **Shopping Cart** - Full cart functionality with order summary
- **Newsletter Subscription** - Stay updated with latest offers

## 📱 Pages

1. **Homepage** (`Homepage.html`)
   - Hero section with call-to-action
   - New arrivals showcase
   - Top selling products
   - Browse by dress style
   - Customer reviews

2. **Category Page** (`Category.html`)
   - Product grid with filters
   - Filter sidebar (desktop) / slide-in panel (mobile)
   - Pagination
   - Sort options

3. **Product Detail Page** (`Product_detail.html`)
   - Product image gallery with thumbnails
   - Color and size selection
   - Quantity selector
   - Product reviews and ratings
   - Related products

4. **Shopping Cart** (`cart.html`)
   - Cart items with quantity controls
   - Order summary
   - Promo code input
   - Checkout button

## 🎨 Design Features

- **Typography**: Custom fonts (Clash Display, Satoshi)
- **Color Scheme**: Minimalist with black, white, and neutral tones
- **Responsive Breakpoints**:
  - Desktop: > 1024px
  - Tablet: 768px - 1024px
  - Mobile: < 768px

## 🛠️ Technologies Used

- HTML5
- CSS3 (with nested selectors)
- Vanilla JavaScript (for interactive elements)
- Custom fonts

## 📂 Project Structure

```
shop-co/
├── Homepage.html
├── Homepage.css
├── Category.html
├── Category.css
├── Product_detail.html
├── Product_detail.css
├── cart.html
├── cart.css
├── Fonts/
│   ├── clash-display.css
│   ├── ClashDisplay-Variable.ttf
│   ├── satoshi.css
│   └── Satoshi-Variable.ttf
├── Images/
│   └── [product images, icons, etc.]
└── README.md
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/shop-co.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd shop-co
   ```

3. **Open in browser**
   - Simply open `Homepage.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     ```

4. **View the website**
   - Open `http://localhost:8000` in your browser

## 📱 Responsive Features

### Desktop (> 1024px)
- Full navigation bar with search
- Side-by-side layouts
- Multi-column product grids
- Visible filter sidebar

### Tablet (768px - 1024px)
- Hamburger menu navigation
- Adjusted layouts
- 2-column product grids
- Slide-in filter panel

### Mobile (< 768px)
- Compact hamburger menu
- Stacked layouts
- Single-column product grids
- Touch-friendly buttons
- Optimized images

## 🎯 Key Components

### Navigation
- Responsive hamburger menu
- Animated menu transitions
- Search functionality
- Cart and profile icons

### Product Cards
- Product images
- Star ratings
- Price display with discounts
- Hover effects

### Filters (Category Page)
- Category filters
- Price range
- Color selection
- Size options
- Toggle button for mobile

### Cart System
- Add/remove items
- Quantity adjustment
- Price calculation
- Discount codes

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Customization

### Colors
Edit CSS variables in each CSS file:
```css
:root {
  --font-heading: "ClashDisplay-Variable", sans-serif;
  --font-body: "Satoshi-Variable", sans-serif;
}
```

### Breakpoints
Modify media queries in CSS files:
```css
@media (max-width: 1024px) { /* Tablet */ }
@media (max-width: 768px) { /* Tablet Portrait */ }
@media (max-width: 480px) { /* Mobile */ }
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Your Name
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- Design inspiration from modern e-commerce platforms
- Icons and images from respective sources
- Fonts: Clash Display and Satoshi

## 📧 Contact

For any questions or suggestions, please reach out:
- Email: your.email@example.com
- Project Link: [https://github.com/yourusername/shop-co](https://github.com/yourusername/shop-co)

---

⭐ Star this repo if you find it helpful!
