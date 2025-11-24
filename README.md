# Courtney Barnett Website

A responsive website showcasing Courtney Barnett with image galleries and interactive features.

## Features

- **Sticky Navigation Menu** - Header becomes sticky when scrolling
- **Lightbox Gallery** - Click on images to view in fullscreen lightbox
- **Image Slider** - Smooth horizontal slider with automatic transitions
- **Responsive Design** - Works on desktop and mobile devices

## Technologies Used

- HTML5
- CSS3 (with custom styling)
- JavaScript (jQuery)
- Lightbox2 for image galleries
- Slippry.js for image sliders

## Live Demo

🌐 **Live Site:** [https://courtney-barnett-website.netlify.app](https://courtney-barnett-website.netlify.app)

🌐 **Live Site:**  https://niko5886.github.io/courtney-barnett-website/

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/Niko5886/courtney-barnett-website.git
   ```

2. Open `index.html` in your web browser

3. For development with live reload, you can use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## Project Structure

```
├── index.html              # Main HTML file
├── css/
│   ├── default.css         # Main stylesheet
│   ├── lightbox.css        # Lightbox styling
│   └── slippry.css         # Slider styling
├── js/
│   ├── jquery-3.5.1.js     # jQuery library
│   ├── lightbox.js         # Lightbox functionality
│   └── slippry.min.js      # Slider functionality
├── Court_Barn_img/         # Image gallery
├── fonts/                  # Web fonts
└── images/                 # Additional images
```

## Deployment

This site is automatically deployed to Netlify. Any changes pushed to the main branch will trigger a new deployment.

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).
