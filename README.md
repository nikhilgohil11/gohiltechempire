# Gohil Tech Empire - Company Website

A modern, responsive website for Gohil Tech Empire showcasing the company's directors, Nikhil Gohil and Vikas Gohil, and their portfolio of 100 innovative products.

## 🌟 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Smooth scrolling and mobile-friendly hamburger menu
- **Product Showcase**: 100 products organized into 4 categories with filtering
- **Director Profiles**: Dedicated sections for Nikhil and Vikas Gohil
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 📁 File Structure

```
Company Website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local Development**: Use a local server for best experience:
   - Python: `python -m http.server 8000`
   - Node.js: `npx serve .`
   - VS Code: Use the "Live Server" extension

## 📱 Website Sections

### 1. Hero Section
- Company introduction with call-to-action
- Animated tech sphere with floating effect

### 2. About Section
- Company description and mission
- Key statistics (100+ Products, 2 Directors, ∞ Possibilities)

### 3. Directors Section
- **Nikhil Gohil**: Technical Director with development expertise
- **Vikas Gohil**: Marketing Director with strategic marketing skills
- Professional cards with skill tags

### 4. Products Section
- **100 Products** organized into 4 categories:
  - **Software** (25 products): Enterprise software solutions
  - **Mobile Apps** (25 products): iOS and Android applications
  - **Web Solutions** (25 products): Web platforms and services
  - **AI & ML** (25 products): Artificial Intelligence and Machine Learning

### 5. Contact Section
- Contact information with icons
- Functional contact form with validation

## 🎨 Customization

### Changing Company Information
Edit the following sections in `index.html`:
- Company name and tagline in the hero section
- About section content
- Director information and descriptions
- Contact details

### Modifying Products
The products are defined in `script.js`. Each product has:
```javascript
{
    name: "Product Name",
    category: "software|mobile|web|ai",
    icon: "fas fa-icon-name",
    link: "https://product-website.com"
}
```

### Styling Changes
- Colors: Modify CSS variables in `styles.css`
- Fonts: Change Google Fonts import in `index.html`
- Layout: Adjust grid and flexbox properties in `styles.css`

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons for products and UI elements
- **Google Fonts**: Poppins font family

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

### Performance Features
- Optimized images and icons
- Smooth animations with CSS transitions
- Lazy loading for product cards
- Responsive images and layouts

## 📧 Contact Information

The website includes placeholder contact information. Update these in `index.html`:
- Email: info@gohiltechempire.com
- Phone: +1 (555) 123-4567
- Address: Innovation Hub, Tech District

## 🚀 Deployment

### Static Hosting
The website can be deployed to any static hosting service:
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Push to a GitHub repository
- **AWS S3**: Upload files to S3 bucket

### Custom Domain
1. Purchase a domain (e.g., gohiltechempire.com)
2. Configure DNS settings
3. Update the website with your domain

## 🔄 Updates and Maintenance

### Adding New Products
1. Open `script.js`
2. Add new product object to the `products` array
3. Include appropriate icon and category
4. Add website link

### Updating Director Information
1. Edit the director cards in `index.html`
2. Update descriptions, skills, and roles
3. Add real photos by replacing the icon elements

### Changing Colors/Styles
1. Modify CSS variables in `styles.css`
2. Primary color: `#2563eb`
3. Secondary color: `#667eea`
4. Background gradients and hover effects

## 📞 Support

For technical support or customization requests:
- Email: support@gohiltechempire.com
- Website: https://gohiltechempire.com

## 📄 License

This website template is created for Gohil Tech Empire. All rights reserved.

---

**Built with ❤️ for Gohil Tech Empire**
*Empowering the future through innovative technology solutions* 