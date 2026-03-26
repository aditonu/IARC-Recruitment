The Dholakpur Shop 🛍️
A modern, high-performance E-commerce storefront inspired by major Indian marketplaces. Built with a focus on a "curated" shopping experience, The Dholakpur Shop features a sleek, dark-mode-ready interface and a fully functional shopping cart system.

✨ Key Features
Adaptive Theme Engine: Seamlessly switch between Light and Dark modes with persistence via localStorage.

Dynamic Product Catalog:

Curated categories: Electronics, Fashion, Beauty, Travel, Appliances, and Home Goods.

Real-time search and filtering.

Multi-criteria sorting (Price, Name, and Featured).

Interactive Shopping Experience:

Hero Slideshow: Auto-playing promotional banners.

Product Overlays: Detailed views with auto-generated Flipkart comparison links.

Persistent Cart: Add, remove, and adjust quantities with real-time price calculation and "Price Details" summaries.

Custom Checkout Flow: A unique "Scan to Pay" UPI integration simulation.

Witty Interaction: Includes custom sound effects (faah.mp3) and Easter eggs (like the "B2 Bomber" delivery status).

🛠️ Tech Stack
Frontend: HTML5, CSS3.

Styling: Tailwind CSS (via Play CDN).

Typography & Icons: Inter Font, Material Symbols Outlined.

Logic: Vanilla JavaScript (ES6+).

Data Management: localStorage for cart and theme persistence.

📂 File Structure
Plaintext
├── index.html          # Main application structure and logic
├── faah.mp3            # Custom subscription sound effect
├── image_b512ad.jpg    # Payment QR code for checkout
└── README.md           # Project documentation
🚀 Getting Started
Clone the project: Ensure all assets (like faah.mp3) are in the same directory as index.html.
  
Open in Browser: Simply double-click index.html or use a "Live Server" extension in VS Code.

Explore:

Search for "iPhone" or "Puma" in the search bar.

Add items to your cart and check the subtotal breakdown.

Try the "Stay in the Loop" email subscription to hear the signature sound!

📝 Development Notes
Responsive Design: The grid layout adapts from 2 columns on mobile to 5 columns on ultra-wide screens.

State Management: The application uses a central cart array and customProducts object to manage UI state without external frameworks.

Designed & Built By Tony “Maximizing value and selection for every customer.”
