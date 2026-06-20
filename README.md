# Travel Explorer 🌍✈️

A beautiful and responsive travel website designed to inspire wanderlust and help users discover their next adventure. Travel Explorer showcases popular destinations, adventure tours, travel tips, and more.

**Live Demo:** [https://petkov93.github.io/TravelExplorer](https://petkov93.github.io/TravelExplorer)

---

## 📋 Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Sections Overview](#sections-overview)
- [Customization](#customization)
- [License](#license)

---

## ✨ Features

- **Hero Section** - Eye-catching banner with a mountain-sea background and call-to-action button
- **Popular Destinations** - Showcase of featured travel destinations (Santorini, Kyoto, Banff)
- **Adventure Tours** - Highlighted tours section with descriptive content
- **Travel Tips Sidebar** - Curated travel advice including packing tips, budget travel, and hiking gear
- **Photo of the Day** - Daily featured travel photography (Maldives Paradise)
- **Icon Section** - Visual representation of travel activities
- **Footer with Newsletter** - Newsletter subscription, quick links, social media, and site information
- **Responsive Design** - Mobile-friendly layout powered by CSS Flexbox
- **Modern UI** - Clean design with orange accent colors and professional typography

---

## 📁 Project Structure

```
TravelExplorer/
├── index.html          # Main HTML file
├── styles/
│   ├── reset.css       # CSS reset for consistent styling
│   └── styles.css      # Main stylesheet with all page styles
├── images/             # Image assets
│   ├── mountain-sea-view.png
│   ├── santorini.jpeg
│   ├── kyoto-japan.webp
│   ├── baniff-canada.jpg
│   ├── woman-lake.avif
│   ├── the_maldives_paradise.avif
│   └── [SVG icons]
└── README.md           # This file
```

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling, Flexbox layout, and responsive design
- **Google Fonts** - Custom typography (Poppins, Raleway, Alex Brush)
- **Font Awesome 7.0.1** - Icon library for visual elements
- **Responsive Design** - Mobile-first approach with flexible layouts

**Language Composition:**
- HTML: 58.3%
- CSS: 41.7%

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/petkov93/TravelExplorer.git
   cd TravelExplorer
   ```

2. **Open in browser:**
   - Simply double-click `index.html` to open locally, or
   - Use a local server for best results:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```
   - Visit `http://localhost:8000` in your browser

3. **Deploy to GitHub Pages:**
   - The site is configured for GitHub Pages deployment
   - Access it at: https://petkov93.github.io/TravelExplorer

---

## 🎨 Sections Overview

### Header & Navigation
- Logo with Travel Explorer branding
- Navigation menu (Home, Destinations, Tours, Blog, Contact)
- "Get Started" call-to-action button

### Hero Section (`discover-section`)
- Large background image with dark text overlay
- Headline: "Discover Your Next Adventure"
- Tagline and prominent "Start Your Journey" button

### Main Content (`mid-section`)
- **Left Column (70% width):**
  - Popular Destinations with image cards
  - Adventure Tours section with imagery
  
- **Right Column (30% width):**
  - Travel Tips with links to articles
  - Photo of the Day feature

### Icon Section
- Visual icons representing travel themes (mountains, locations, camera, suitcase, etc.)

### Footer
- About Us section
- Quick Links
- Social Media links (Facebook, Twitter, Instagram)
- Newsletter subscription form

---

## 🎨 Customization

### Changing Colors
The primary accent color is orange (`#f26826`). To change it:
- Search for `#f26826` in `styles/styles.css`
- Replace with your desired color

### Adding/Updating Destinations
Edit the `Popular Destinations` section in `index.html`:
```html
<div class="img-wrapper">
    <p>Your Destination</p>
    <img src="./images/your-image.jpg" alt="Your Destination">
</div>
```

### Updating Travel Tips
Modify the `Travel Tips` list in `index.html`:
```html
<li>
    <i class="fa-solid fa-square-check"></i>
    <a href="#">Your Tip Title</a>
</li>
```

### Connecting Newsletter Form
The newsletter form (lines 153-156) currently has empty `action` and `method` attributes. Connect it to your backend:
```html
<form action="your-backend-endpoint" method="POST">
    <input type="email" placeholder="Enter Your Email" required>
    <button class="orange-btn" type="submit">Subscribe</button>
</form>
```

---

## 📝 Future Enhancements

Potential improvements for the project:
- Add JavaScript functionality for interactive features
- Connect the newsletter form to an email service
- Add more destination cards and tours
- Implement a blog section
- Add contact form functionality
- Optimize images for faster loading
- Add smooth scrolling and animations
- Create a mobile navigation menu

---

## 📧 Contact & Social

Follow Travel Explorer on social media and stay updated on travel inspiration!

- 📘 Facebook
- 𝕏 Twitter
- 📸 Instagram

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Created by:** [petkov93](https://github.com/petkov93)  
**Repository:** [TravelExplorer](https://github.com/petkov93/TravelExplorer)  
**Last Updated:** February 2026
