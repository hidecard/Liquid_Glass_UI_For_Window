# DWMBlurGlass Usage Guide Website

A beautiful, modern web page showcasing the DWMBlurGlass application with glass morphism effects and interactive elements.

## Features

- **Modern Glass Morphism Design**: Beautiful glass-like effects with backdrop blur
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth animations, tab switching, and hover effects
- **Accessibility**: Keyboard navigation and screen reader support
- **Performance Optimized**: Debounced scroll events and efficient animations

## Files Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styling with glass morphism effects
├── script.js           # JavaScript for interactivity
└── web-readme.md       # This file
```

## How to Use

1. **Open the website**: Simply open `index.html` in any modern web browser
2. **Navigate**: Use the navigation menu to jump to different sections
3. **Interactive Tabs**: Click on the tab buttons in the Usage section to explore different settings
4. **Mobile Friendly**: The website automatically adapts to mobile devices

## Customization

### Colors
The website uses CSS custom properties (variables) for easy color customization. Edit the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --accent-color: #06b6d4;
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* ... more variables */
}
```

### Content
- **Features**: Edit the features section in `index.html` to add or modify features
- **Installation Steps**: Update the installation steps in the installation section
- **Troubleshooting**: Modify the troubleshooting cards and error messages

### Animations
Customize animations by editing the keyframes in `styles.css`:

```css
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}
```

## Browser Support

- Chrome 88+
- Firefox 87+
- Safari 14+
- Edge 88+

## Performance Tips

1. **Optimize Images**: If you add images, compress them for web use
2. **Minimize HTTP Requests**: The website uses CDN for fonts and icons
3. **Enable Compression**: Serve files with gzip compression on your web server

## Deployment

### Local Development
Simply open `index.html` in a web browser for local development.

### Web Server Deployment
Upload all files to your web server:
- `index.html`
- `styles.css`
- `script.js`

### GitHub Pages
1. Create a new repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://username.github.io/repository-name`

## Credits

- **Fonts**: Inter font family from Google Fonts
- **Icons**: Font Awesome 6.0
- **Design**: Glass morphism inspired by modern UI trends
- **Original Project**: [DWMBlurGlass](https://github.com/hidecard/Liquid_Glass_UI_For_Window)

## License

This web project is open source and available under the same license as the original DWMBlurGlass project.

## Support

For issues with the website or suggestions for improvements, please create an issue in the repository.

---

**Note**: This is a static website showcasing the DWMBlurGlass application. The actual DWMBlurGlass software is a separate Windows application that needs to be downloaded and installed separately. 