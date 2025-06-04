Game Theory Helper
A web application that applies game theory principles to help you make optimal decisions. Compare multiple choices by evaluating their potential outcomes and get data-driven recommendations.

Features
Smart Decision Making
•	Multiple Choice Comparison - Evaluate unlimited options simultaneously
•	Outcome-Based Analysis - Rate potential results on a 1-10 scale
•	Mathematical Optimization - Uses expected value calculations to find the best choice
•	Real-time Results - Instant feedback as you input data

Visual Analytics
•	Interactive Radar Charts - Compare choices across multiple outcome dimensions
•	Responsive Visualizations - Charts adapt to your data and screen size
•	Dark/Light Mode Support - Comfortable viewing in any lighting condition

Export & Share
•	PDF Generation 
•	Image Export 
•	Text Sharing - Copy results to clipboard or share via native APIs
•	Cross-Platform Compatibility - Works on desktop, tablet, and mobile

Modern Web App
•	Progressive Web App (PWA) - Install and use offline
•	Responsive Design - Optimized for all screen sizes
•	Keyboard Shortcuts - Press Enter to evaluate choices quickly
•	Local Storage - Remembers your theme preference

How to Use
1.	Add Choices - Click "Add Choice" to create options you're considering
2.	Define Outcomes - For each choice, list possible results with importance ratings (1-10)
3.	Evaluate - Click "Evaluate Best Choice" to see the mathematically optimal decision
4.	Analyze - Review the radar chart to understand how choices compare
5.	Export - Save or share your analysis using the export buttons
   
Example Scenarios

Study Abroad Decision:
•	Choice 1: London (friends: 8, career: 7, cost: 4)
•	Choice 2: Paris (adventure: 9, career: 6, cost: 6)

Career Move:
•	Choice 1: Startup (growth: 9, stability: 4, salary: 6)
•	Choice 2: Corporate (growth: 6, stability: 8, salary: 8)

Technical Details

Built With
•	Vanilla JavaScript - No heavy frameworks, fast and lightweight
•	Chart.js - Interactive and responsive charts
•	HTML5 Canvas - High-quality chart rendering
•	CSS3 - Modern styling with CSS custom properties
•	PWA APIs - Service worker for offline functionality

Dependencies
•	Chart.js - Data visualization
•	html2canvas - Screenshot generation
•	jsPDF - PDF export functionality

Browser Support
•	✅ Chrome 80+
•	✅ Firefox 75+
•	✅ Safari 13+
•	✅ Edge 80+
•	✅ Mobile browsers (iOS Safari, Chrome Mobile)

Getting Started

Quick Start
1.	Download the files or clone this repository
2.	Open index.html in any modern web browser
3.	Start adding your choices and outcomes

# Navigate to the project directory
cd game-theory-helper

# Serve with any local server (example with Python)
python -m http.server 8000

# Or use Node.js serve
npx serve .

# Open in browser
open http://localhost:8000

PWA Installation

The app can be installed as a Progressive Web App:
1.	Visit the app in Chrome or Edge
2.	Click the "Install" button in the address bar
   
Project Structure

game-theory-helper/
├── index.html          # Main application file
├── manifest.json       # PWA manifest
├── sw.js              # Service worker for offline support
├── icon-192.png       # App icon (192x192)
├── icon-512.png       # App icon (512x512)
└── README.md          # This file

Customization

Themes
The app supports automatic dark/light mode detection and manual toggling.

Adding New Features
The modular JavaScript structure makes it easy to extend:
•	Add new outcome types
•	Implement additional calculation methods
•	Create custom export formats
•	Integrate with external APIs

Contributing

Contributions are welcome! Here are some ways you can help:
1.	Report Bugs - Found an issue? Open an issue with details
2.	Suggest Features - Have ideas for improvements? Let's discuss them
3.	Submit Pull Requests - Code contributions are appreciated
4.	Improve Documentation - Help make the README even better
   
Development Guidelines
•	Keep code vanilla JavaScript (no frameworks)
•	Maintain responsive design principles
•	Test across different browsers and devices
•	Follow existing code style and patterns

Use Cases

Personal Decisions
•	Education: University selection, course choices
•	Career: Job offers, career pivots, skill development
•	Lifestyle: Moving locations, major purchases, relationship decisions

Business Applications
•	Strategy: Market entry, product features, resource allocation
•	Operations: Vendor selection, process improvements, technology adoption
•	Investment: Portfolio decisions, risk assessment, opportunity evaluation

Academic & Research
•	Decision Theory: Teaching and learning decision-making frameworks
•	Behavioral Economics: Studying choice patterns and biases
•	Operations Research: Practical applications of optimization methods

Future Enhancements
•	[ ] Advanced Algorithms - Monte Carlo simulations, sensitivity analysis
•	[ ] Collaboration Features - Share decisions with teams, collect input
•	[ ] Data Import - CSV/Excel import for large datasets
•	[ ] Template Library - Pre-built decision templates for common scenarios
•	[ ] Historical Tracking - Save and compare past decisions
•	[ ] Mobile Apps - Native iOS and Android versions

License
This project is open source and available under the MIT License.

Acknowledgments
•	Inspired by classical game theory and decision analysis
•	Built with modern web standards and best practices
•	Icons and design elements follow contemporary UI trends
 
Made by Nik with ❤️ for better decision making

