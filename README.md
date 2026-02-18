# Theam Ratana CMS Website

A modern, responsive content management system website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional interface with smooth animations
- **Multiple Pages**: Home, About, Blog, and Contact pages
- **Interactive Elements**: Mobile navigation, smooth scrolling, and form validation
- **SEO Friendly**: Semantic HTML and proper meta tags
- **Fast Loading**: Optimized assets and minimal dependencies

## Project Structure

```
tr_web/
├── index.html          # Homepage
├── about.html          # About page
├── blog.html           # Blog listing page
├── contact.html        # Contact page with form
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
└── README.md           # Documentation
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local web server for development

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/theamratana/tr_web.git
   cd tr_web
   ```

2. Open `index.html` in your web browser, or use a local development server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## Pages

### Home (`index.html`)
- Hero section with call-to-action buttons
- Key features showcase
- Call-to-action section
- Responsive navigation

### About (`about.html`)
- Company/project information
- Mission and vision statements
- Core values display

### Blog (`blog.html`)
- Article listing grid
- Sample blog posts
- Pagination
- Post categories and dates

### Contact (`contact.html`)
- Contact information
- Interactive contact form
- Form validation
- Success/error messages

## Customization

### Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    /* ... more variables */
}
```

### Content
- Update text content directly in the HTML files
- Modify navigation links in each page's `<nav>` section
- Add or remove sections as needed

### JavaScript Features
Located in `js/main.js`:
- Mobile navigation toggle
- Smooth scrolling
- Contact form validation
- Scroll animations
- Navbar scroll effects

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or support, please contact us through the contact form on the website.

## Acknowledgments

- Built with modern web standards
- Responsive design principles
- Accessibility best practices

---

**Theam Ratana CMS** - Building better websites, one page at a time.