# Megamind Innovative School - Landing Page

A modern, responsive landing page for Megamind Innovative School featuring bilingual support (English/Hindi), smart design, and comprehensive school information.

## Features

### 🌐 Bilingual Support
- **English & Hindi** language toggle
- All content stored in JSON format for easy translation
- Seamless language switching without page reload

### 📱 Responsive Design
- Mobile-first approach
- Optimized for all screen sizes
- Modern, clean UI with child-friendly colors

### 🏫 School Information Sections
1. **Hero Section** - School name, tagline, and CTA buttons
2. **About Section** - Vision, mission, and teaching approach
3. **Classes** - Nursery to Class 10 with age groups and focus areas
4. **Boarding Facilities** - Optional boarding with safety and comfort features
5. **Student Life** - Smart classes, computer labs, activities, and sports
6. **Educational Trips** - Learning beyond classrooms across Bihar
7. **Location & Contact** - Google Maps integration and contact details
8. **Social Proof** - Facebook integration

### 🛠 Technical Features
- **Static Website** - No backend required
- **SEO Optimized** - Proper meta tags and structure
- **Fast Loading** - Optimized CSS and JavaScript
- **Google Maps Embed** - Cost-effective map integration
- **Social Media Integration** - Facebook page linking
- **Smooth Animations** - Scroll-based animations and hover effects

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality and language switching
└── README.md           # Documentation
```

## Setup Instructions

1. **Clone or Download** the files to your local directory
2. **Customize Content**:
   - Update school address in the location section
   - Replace placeholder phone number and email
   - Update Google Maps embed URL with actual location
   - Replace Facebook URL with actual page
3. **Deploy** to any static hosting service:
   - **Netlify**: Drag and drop the folder
   - **Vercel**: Connect GitHub repository
   - **GitHub Pages**: Push to repository and enable Pages

## Customization Guide

### Content Updates
All text content is stored in the `content` object in `script.js`:

```javascript
const content = {
    en: {
        schoolName: "Megamind Innovative School",
        heroTagline: "Your custom tagline here",
        // ... more content
    },
    hi: {
        schoolName: "मेगामाइंड इनोवेटिव स्कूल",
        // ... Hindi translations
    }
};
```

### Contact Information
Update these placeholders in `index.html`:
- Phone: `+91-XXXXXXXXXX`
- Email: `info@megamindinnovative.edu`
- Address: Update the address text and Google Maps embed URL

### Google Maps Integration
Replace the iframe src in the location section with your actual Google Maps embed URL:
```html
<iframe src="YOUR_GOOGLE_MAPS_EMBED_URL"></iframe>
```

### Colors and Styling
Main color variables in `styles.css`:
- Primary Blue: `#2563eb`
- Success Green: `#10b981`
- Background: `#f8fafc`

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features
- Optimized images and icons using Font Awesome
- Minimal JavaScript for fast loading
- CSS Grid and Flexbox for efficient layouts
- Lazy loading for smooth scrolling animations

## SEO Features
- Semantic HTML structure
- Meta descriptions and titles
- Proper heading hierarchy
- Alt texts for accessibility
- Schema markup ready

## Deployment Options

### Netlify (Recommended)
1. Drag and drop the project folder to Netlify
2. Your site will be live instantly with HTTPS

### Vercel
1. Push code to GitHub
2. Connect repository to Vercel
3. Deploy with automatic builds

### GitHub Pages
1. Push to GitHub repository
2. Enable Pages in repository settings
3. Select source branch

## Future Enhancements
- Contact form integration
- Online admission form
- Photo gallery
- News and events section
- Student portal integration
- WhatsApp chat integration

## Support
For customization help or technical support, please refer to the documentation or contact the development team.

---

**Built with ❤️ for Megamind Innovative School**