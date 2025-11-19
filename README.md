# CancerMonitor - Early Cancer Detection Platform

A modern, responsive website for a health monitoring company that helps people detect cancer early through blood testing, dietary management, and continuous glucose monitoring.

## Features

- **Three Key Cancer Metrics**: Comprehensive blood testing for tumor markers, inflammatory markers, and genetic markers
- **Dietary Guidance**: Evidence-based recommendations for reducing blood sugar levels
- **Real-time Tracking**: Wireless glucometer integration for continuous glucose monitoring
- **Continuous Monitoring Cycle**: Repeat testing and tracking to monitor improvements over time

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser

### For Development

If you want to run a local server (recommended):

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## Project Structure

```
cancer/
├── index.html      # Main HTML file
├── styles.css      # All styling and responsive design
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## Features Breakdown

### 1. Hero Section
- Eye-catching landing area with call-to-action
- Key statistics display
- Smooth animations

### 2. Three Key Metrics Section
- **Tumor Markers**: CEA, CA 19-9, PSA
- **Inflammatory Markers**: CRP, ESR, IL-6
- **Genetic Markers**: ctDNA, MicroRNA, Methylation

### 3. Diet Section
- Benefits of reducing blood sugar
- Dietary recommendations
- Visual food wheel animation

### 4. Tracking Section
- Simulated glucose monitor display
- Real-time tracking features
- Progress visualization

### 5. How It Works / Cycle Section
- Step-by-step process visualization
- Continuous monitoring cycle explanation
- Key benefits highlighted

### 6. Call-to-Action Section
- Lead capture form
- Contact information collection

## Customization

### Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #10b981;
    --accent-color: #f59e0b;
    /* ... */
}
```

### Content
All content is in `index.html`. Simply edit the text within the HTML tags.

### Form Submission
The form currently shows an alert. To connect to a backend:

1. Update the form action in `index.html`
2. Modify the form submission handler in `script.js`
3. Add your backend endpoint

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Responsive Design

The website is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## Medical Disclaimer

**Important**: This website provides general health information and should not replace professional medical advice, diagnosis, or treatment. Always consult with qualified healthcare providers for medical concerns.

## License

This project is created for CancerMonitor company. All rights reserved.

## Future Enhancements

- Backend integration for form submissions
- User dashboard for tracking metrics
- Integration with actual glucometer APIs
- Patient portal for viewing test results
- Appointment scheduling system
- Educational resources and blog section

## Contact

For questions or support, please use the contact form on the website.

