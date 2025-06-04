# GameTheoryHelper

A modern Progressive Web App (PWA) that helps you make better decisions using game theory principles. Evaluate multiple choices and visualize your decision-making process through interactive radar charts.

##Features

- Interactive Decision Making: Add multiple choices with custom outcomes and values
- Visual Analytics: Interactive radar charts to compare choices across multiple dimensions
- Dark/Light Mode
- Export Options: 
  - Copy results to clipboard
  - Download as PDF
  - Export as PNG image
- Responsive Design
- Motivational Quotes: Philosophical wisdom to inspire thoughtful decision-making

## How to Use

1. Add Your Choices: Click "Add Choice" to create decision options
2. Define Outcomes: For each choice, add specific outcomes with:
   - Name: What the outcome represents (e.g., "Career Growth")
   - Value: How good this outcome is (1-10 scale)
3. Evaluate: Click "Evaluate Best Choice" to see the analysis
4. Visualize: View the radar chart to compare choices across all dimensions
5. Export: Save or share your decision analysis

##Technical Details

### Built With
- Vanilla JavaScript - No frameworks, lightweight and fast
- Chart.js - Interactive radar charts
- HTML5 Canvas - For chart rendering and screenshots
- CSS3 - Modern styling with CSS variables and animations

### Key Technologies
- Progressive Web App (PWA)
  - Service Worker for offline functionality
  - Web App Manifest for installation
  - Responsive design for all devices
- Modern Web APIs
  - Web Share API for native sharing
  - Clipboard API for copy functionality
  - Local Storage for theme preferences
- Export Capabilities**
  - html2canvas for screenshot generation
  - jsPDF for PDF export
  - Canvas API for image generation

### File Structure
```
GameTheoryHelper/
├── index.html          # Main application file
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── icon-192.png       # App icon (192x192)
├── icon-512.png       # App icon (512x512)
└── README.md          # This file
```

### Example Use Cases
- Life Decisions: Choosing between job offers, cities to live in, or schools to attend
- Business Strategy: Evaluating product features, market opportunities, or investment options
- Personal Choices: Selecting vacation destinations, major purchases, or relationship decisions

## 🔒 Privacy & Security

- No Data Collection**: All processing happens locally in your browser
- No Server Required**: Everything runs client-side
- Privacy First: Your decisions never leave your device

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

### Ideas for Contribution
- Add more decision-making algorithms (e.g., AHP, TOPSIS)
- Implement data import/export (CSV, JSON)
- Add more chart types (bar charts, scatter plots)
- Enhance accessibility features
- Add internationalization support
- Create decision templates for common scenarios


## Acknowledgments

- Inspired by classical game theory and decision science
- Uses modern web technologies for a seamless experience
- Quotes from Stoic philosophers for wisdom and reflection
- Built with accessibility and user experience in mind

## Browser Support

- Chrome/Chromium (full PWA support)
- Firefox (partial PWA support)
- Safari (iOS PWA support)
- Edge (full PWA support)
- Internet Explorer (not supported)

## Known Issues

- PDF export may not work perfectly on all mobile browsers


## Future Enhancements

- [ ] Decision history and comparison
- [ ] Advanced algorithms (Monte Carlo, sensitivity analysis)
- [ ] Collaborative decision making
- [ ] Decision templates library
- [ ] Data visualization improvements
- [ ] AI-powered decision insights

---

Made with ❤️ by Nik for better decision making

Remember: This tool aids your decision-making process, but the final choice is always yours. Use it as a guide, not a replacement for critical thinking and personal judgment.
