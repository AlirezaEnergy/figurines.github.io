# Figurine Collection Shop

A static website showcasing collectible figurines and statues for sale. This website is designed to be hosted on GitHub Pages and provides an easy way to display products with contact information for potential buyers.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **3-Column Grid Layout**: Displays 30 products in an organized grid
- **Hover Effects**: Interactive product cards with smooth animations
- **Contact Information**: Easy access to contact details for purchasing
- **Modern UI**: Clean, professional design with gradient headers

## File Structure

```
shopping_site/
├── index.html          # Main HTML file with 30 product cards
├── styles.css          # CSS styling and responsive design
└── README.md          # This file
```

## Customization

### Adding Your Own Product Images

1. Replace the placeholder image URLs in `index.html` with your actual product images
2. Currently using placeholder images from `via.placeholder.com`
3. Update the `alt` text for each image to describe your actual products

### Updating Product Information

Edit the following in each product card in `index.html`:
- Product title (`<h3>` tag)
- Price (`.price` class)
- Description (`.description` class)

### Updating Contact Information

Edit the contact section in `index.html`:
- Email: Replace `your-email@example.com` with your actual email
- Phone: Replace `+1 (234) 567-890` with your phone number
- Location: Update with your city and state
- Social links: Update the href attributes with your actual social media URLs

## GitHub Pages Hosting

### Method 1: Using GitHub Interface

1. Create a new repository on GitHub named `username.github.io` (replace `username` with your GitHub username)
2. Upload the `index.html` and `styles.css` files to the repository
3. Your site will be available at `https://username.github.io`

### Method 2: Using Git Command Line

1. Create a new repository on GitHub
2. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
   ```
3. Copy your files to the repository:
   ```bash
   cp /path/to/shopping_site/* .
   ```
4. Add, commit, and push:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```
5. Enable GitHub Pages in repository settings:
   - Go to Settings → Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

### Method 3: Using GitHub Desktop

1. Create a new repository on GitHub
2. Clone it using GitHub Desktop
3. Copy the `index.html` and `styles.css` files to the repository folder
4. Commit changes with description "Initial commit"
5. Push to GitHub
6. Enable GitHub Pages in repository settings

## Customization Tips

### Colors and Styling

Edit `styles.css` to customize:
- Header gradient: Modify the `background` property in `header` selector
- Product card colors: Update `background`, `box-shadow` properties
- Text colors: Modify `color` properties throughout the file
- Hover effects: Adjust transitions and transform values

### Adding More Products

To add more than 30 products:
1. Copy an existing product card in `index.html`
2. Paste it at the end of the `.products` section
3. Update the product information
4. Add animation delay for the new product in `styles.css`

### Removing Products

To remove products:
1. Delete the corresponding `<div class="product-card">` elements from `index.html`
2. Remove the animation delay rules from `styles.css`

## Browser Compatibility

This website is compatible with:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Support

For issues or questions about the website:
1. Check that all files are in the same directory
2. Verify image URLs are accessible
3. Ensure CSS file is properly linked in HTML
4. Test in different browsers for compatibility

## License

This project is open source and available under the [MIT License](LICENSE).
